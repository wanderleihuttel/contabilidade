### Bloquear Atualização do Firefox

Efetuar o download do Firefox Portable no link abaixo:

https://portableapps.com/apps/internet/firefox_portable

Execute para efetuar a instalação.

- Crie um arquivo chamado **policies.json** com o contéudo abaixo:
````
{
    "policies": {
        "AppUpdateURL": "http://127.0.0.1/",
        "DisableAppUpdate": true,
        "DisableFirefoxStudies": true,
        "DisableSystemAddonUpdate": true,
        "DisableTelemetry": true,
        "ExtensionUpdate": false,
        "DisableFirefoxAccounts": true,
        "DontCheckDefaultBrowser": true
    }
}
````

FirefoxPortable\App\Firefox64
FirefoxPortable\App\Firefox

Dentro da pasta do **FirefoxPortable**, procure pela pasta onde se encontra os binários executáveis do Firefox.
Geralmente é:
- FirefoxPortable\App\Firefox64
- FirefoxPortable\App\Firefox


Crie uma pasta chamada "distribution" em ambas as pastas mencionadas acima e copie e cole o arquivo **policies.json**.
