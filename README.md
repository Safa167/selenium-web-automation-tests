# selenium-web-automation-tests
#  Automatización de Pruebas Web con Selenium]

## Descripción
Este proyecto contiene scripts de automatización de pruebas web desarrollados con Selenium. El objetivo es demostrar la capacidad de crear y ejecutar pruebas automatizadas para asegurar la funcionalidad y estabilidad de aplicaciones web.

Este repositorio alberga una suite de pruebas automatizadas para el sitio web 'demoblaze.com' o 'The Internet (Heroku App)'. Las pruebas están diseñadas para verificar funcionalidades clave como el registro de usuarios, el inicio de sesión y la navegación por productos.

## Problema/Objetivo
 El objetivo principal de este proyecto es validar la robustez y funcionalidad crítica de una aplicación web, identificando posibles defectos de manera temprana y asegurando una experiencia de usuario sin interrupciones. Demuestra mi habilidad para diseñar, implementar y ejecutar pruebas de regresión automatizadas.

## Tecnologías Utilizadas
- **Lenguaje de Programación:** [Ej. Python, Java, JavaScript, C#]
- **Framework de Testing (si usas uno específico):** [Ej. Pytest, JUnit, TestNG, NUnit, Cypress, Jest]
- **Biblioteca de Automatización Web:** [**Selenium WebDriver**]
- **Manejador de Navegador:** [Ej. ChromeDriver, GeckoDriver (Firefox), EdgeDriver, etc.]
- **Control de Versiones:** Git
- **Plataforma de Alojamiento de Código:** GitHub

## Cómo Ejecutar el Proyecto


1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/SeleniumHQ/selenium]
    ```
2.  **Navega al directorio del proyecto:**
    ```bash
    cd selenium-web-automation-tests
    ```
3.  **Instala las dependencias:**
    *Si usas Python:*
    ```bash
    pip install -r requirements.txt
    ```
    (Asegúrate de tener un archivo `requirements.txt` con Selenium y cualquier otra dependencia. Si no lo tienes, créalo con `pip freeze > requirements.txt` después de instalar tus dependencias).
    *Si usas Java/Maven:*
    ```bash
    mvn clean install
    ```
    *Si usas JavaScript/NPM:*
    ```bash
    npm install
    ```
4.  **Configura el Driver del Navegador:**
    Asegúrate de tener el driver del navegador (ej. `chromedriver.exe` para Chrome) en tu PATH del sistema, o especifica su ruta en tu código. Descarga ChromeDriver desde https://developer.chrome.com/docs/chromedriver/downloads?hl=es-419
    
6.  **Ejecuta las pruebas:**
    *Si usas Python y Pytest:*
    ```bash
    pytest
    ```
    *Si usas Java y JUnit/TestNG:*
    ```bash
    mvn test
    ```
    *Si usas JavaScript y Cypress/Jest:*
    ```bash
    npm test
    ```
  


## Lo que Aprendí / Desafíos Superados
Durante el desarrollo de esta suite de pruebas, profundicé en el uso de Page Object Model para mantener el código de prueba limpio y mantenible. Uno de los desafíos fue manejar los 'tiempos de espera asíncronos en elementos dinámicos', lo cual resolví utilizando  'condiciones esperadas de Selenium'."

## Contacto
No dudes en contactarme si tienes preguntas o quieres discutir un proyecto.
- **LinkedIn:** www.linkedin.com/in/tiziana-del-aguila

- **Freelancer.com:** https://www.freelancer.es/u/Tiziani?frm=Tiziani&sb=t
