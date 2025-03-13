# Asistente de Medicamentos

## Descripción
Asistente médico desarrollado utilizando Next.js para el frontend y la API de Gemini para el procesamiento del lenguaje natural. Este proyecto implementa un enfoque de fine-tuning (pre-entrenamiento) con información detallada de medicamentos para proporcionar información precisa y relevante sobre medicamentos y condiciones médicas.

## Características principales
- Proporciona información general sobre medicamentos y condiciones médicas
- Responde en español e inglés según la preferencia del usuario
- Incluye advertencias para consultar a profesionales de la salud
- Provee información sobre dosis solo para medicamentos de venta libre
- Menciona posibles efectos secundarios y contraindicaciones
- Identifica situaciones de emergencia y recomienda atención inmediata

## Tecnologías utilizadas
- Frontend: Next.js
- Procesamiento de lenguaje natural: API de Gemini (gemini-1.5-flash)
- Fine-tuning personalizado con datos de medicamentos

## Capturas de pantalla

### Página de Login
<img width="1097" alt="image" src="https://github.com/user-attachments/assets/05430ab9-0bb3-4e36-b57d-3fca209ca982" />


### Página de Registro
<img width="1097" alt="image" src="https://github.com/user-attachments/assets/9e29d9be-8300-4b89-b2f3-e26b5c66e65e" />


### Interfaz principal del Asistente
![image](https://github.com/user-attachments/assets/c3ebba14-8e96-4dbb-8664-61a8603c44d8)
![image](https://github.com/user-attachments/assets/90fe1130-2062-4246-83d6-e198906f825d)



## Instalación y configuración
1. Clonar el repositorio
2. Instalar dependencias: `pnpm install`
3. Configurar variables de entorno: Crear archivo `.env.local` con `GEMINI_API_KEY=tu_clave_api`
4. Iniciar el servidor de desarrollo: `pnpm run dev`
