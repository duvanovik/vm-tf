# VM-TF LAB Duvan Garcia

## Descripción
Despliega una vm con terraform en azure.

## Prerrequisitos
Para correr este proyecto, simplemente sigue los siguientes pasos:
1. Clona el repositorio en tu máquina local.
2. Configura el login de azure.
3. ¡Listo para empezar a trabajar!

## Uso
1. Inicia terraform (`terraform init`).
2. Correr el terraform plan (`terraform plan -out main.tfplan`).
3. Correr el terraform el apply para ejecutar la infraestructura (`terraform apply main.tfplan`).

## Limpiar los recursos
```
terraform plan -destroy -out main.destroy.tfplan.
```
## Validación
![sss](https://github.com/duvanovik/vm-tf/assets/42594511/df6ce1f6-ea3e-4d7c-afe1-88f6a0b6e509)
