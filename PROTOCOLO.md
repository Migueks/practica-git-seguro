# Protocolo de seguridad del repositorio

Este documento recoge las medidas de seguridad aplicadas durante la práctica.

## 1. Control de versiones
Registrar los cambios mediante commits descriptivos.

## 2. Protección de archivos
Utilizar .gitignore para evitar incorporar archivos innecesarios o sensibles.

## 3. Autenticidad
Firmar commits mediante claves GPG.

## 4. Detección de secretos
Utilizar Gitleaks para identificar posibles credenciales expuestas.

## 5. Prevención
Configurar hooks de Git para comprobar la seguridad antes de confirmar cambios.
