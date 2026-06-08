# EDDM-practica

Proyecto de Unity orientado a XR con dependencias de Meta XR SDK y OpenXR.

## Requisitos

- Unity `6000.3.10f1`
- Git LFS instalado

## Clonar el proyecto

```bash
git clone https://github.com/nargoc/EDDM-practica.git
cd EDDM-practica
git lfs pull
```

## Abrir en Unity

1. Abre Unity Hub.
2. Agrega esta carpeta como proyecto.
3. Usa la version `6000.3.10f1`.
4. Espera a que Unity restaure los paquetes desde `Packages/manifest.json`.

## Escena configurada en Build Settings

- `Assets/Samples/Meta XR Interaction SDK/201.0.0/Example Scenes/HandGrabExamples.unity`

## Paquetes principales

- `com.meta.xr.sdk.all` `201.0.0`
- `com.unity.xr.openxr` `1.16.1`
- `com.unity.inputsystem` `1.18.0`
- `com.unity.render-pipelines.universal` `17.3.0`

## Estructura

- `Assets/`: escenas, recursos y contenido del proyecto
- `Packages/`: manifiesto y bloqueo de dependencias
- `ProjectSettings/`: configuracion del proyecto

## Notas

- El repositorio usa Git LFS para assets binarios habituales de Unity.
- Carpetas generadas por Unity como `Library/`, `Temp/` y builds no se versionan.
