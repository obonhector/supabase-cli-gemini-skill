# Supabase CLI Skill for Gemini CLI 🌑✨

This skill enables **Gemini CLI** to interact natively with **Supabase** using the official `supabase` CLI tool.

---

## 🇪🇸 Descripción (Spanish)
Esta Skill permite a Gemini CLI gestionar bases de datos PostgreSQL, autenticación, funciones Edge y configuraciones de proyectos en la nube de Supabase directamente desde la terminal.

### Características:
- **Desarrollo Local:** Inicializa proyectos, levanta contenedores de Docker y gestiona el entorno local.
- **Bases de Datos:** Gestiona migraciones, genera tipos de TypeScript y sincroniza esquemas.
- **Edge Functions:** Crea, sirve localmente y despliega funciones Edge.
- **Gestión de Proyectos:** Vincula proyectos, gestiona secretos y monitoriza el estado de los servicios en la nube.

---

## 🇺🇸 Description (English)
This skill allows Gemini CLI to manage PostgreSQL databases, Auth, Edge Functions, and Supabase cloud project configurations directly from the terminal.

### Features:
- **Local Development:** Initialize projects, start Docker containers, and manage the local environment.
- **Database Management:** Manage migrations, generate TypeScript types, and sync schemas.
- **Edge Functions:** Create, serve locally, and deploy Edge Functions.
- **Project Management:** Link projects, manage secrets, and monitor cloud service status.

---

## 🚀 Installation / Instalación

1.  **Install Supabase CLI / Instala Supabase CLI:**
    ```bash
    brew install supabase/tap/supabase
    ```

2.  **Clone the repository / Clona el repositorio:**
    ```bash
    git clone https://github.com/obonhector/supabase-cli-gemini-skill.git
    ```

3.  **Install the skill / Instala la skill:**
    ```bash
    gemini skills install ./supabase-cli-gemini-skill --scope user
    ```

4.  **Reload skills / Recarga las skills:**
    In your Gemini CLI session, run:
    ```
    /skills reload
    ```

---

## 💡 Usage Examples / Ejemplos de Uso

- "Inicializa un proyecto de Supabase en esta carpeta"
- "Genera los tipos de TypeScript para mi base de datos"
- "Crea una nueva migración llamada 'add_users_table'"
- "Despliega la función Edge 'newsletter-api'"
- "Dime el estado de mis servicios en Supabase"

---

## 🛠️ Security / Seguridad
Esta skill utiliza la autenticación local de tu sistema. Asegúrate de haber ejecutado `supabase login` antes de intentar gestionar proyectos en la nube. Tus tokens de acceso no se comparten ni se guardan en la skill.

---

## 🤝 Contributing / Contribución
Si quieres añadir más comandos o mejorar la integración, ¡envía una pull request!
