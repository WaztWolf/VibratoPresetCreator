# Vibrato Preset Creator

Vibrato Preset Creator es una aplicación de escritorio construida con Avalonia UI y .NET 8.0 para crear, editar y guardar presets de vibrato en archivos `.cs` y manipular archivos de audio WAV.

## Características principales
- Selección y visualización de archivos WAV.
- Edición y guardado de presets en archivos `.cs`.
- Configuración de dispositivo de salida de audio.
- Interfaz moderna y fácil de usar.

## Requisitos
- .NET 8.0 SDK
- Windows 10/11 (compatible con otras plataformas si Avalonia lo permite)

## Instalación
1. Clona este repositorio:
   ```powershell
   git clone <URL-del-repositorio>
   ```
2. Accede al directorio del proyecto:
   ```powershell
   cd VibratoPresetCreator
   ```
3. Restaura los paquetes y compila:
   ```powershell
   dotnet restore
   dotnet build
   ```

## Ejecución
Para iniciar la aplicación:
```powershell
 dotnet run
```

## Uso
1. Selecciona un archivo WAV usando el botón "Examinar…".
2. Elige el dispositivo de salida de audio.
3. Selecciona o crea un archivo de presets `.cs`.
4. Guarda los cambios usando los botones correspondientes.

## Estructura del proyecto
- `Views/` - Contiene las ventanas y controles visuales (AXAML y CS).
- `Models/` - Modelos de datos para presets y notas.
- `Services/` - Lógica de negocio y servicios de audio, configuración y generación de código.
- `App.axaml` y `Program.cs` - Entrada principal de la aplicación.

## Contribuir
Las contribuciones son bienvenidas. Puedes abrir issues o enviar pull requests.

## Licencia
Este proyecto está bajo la licencia MIT.
