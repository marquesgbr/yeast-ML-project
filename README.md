# yeast-ML-project

## Como preparar o ambiente e rodar os notebooks (Windows)

- OBS: Certifique-se de ter a extensão do jupyter instalada no VSCode.

1. Criar e ativar um virtual environment
- CMD:
  ```cmd
  python -m venv .venv
  .venv\Scripts\activate
  ```
- PowerShell:
  ```powershell
  python -m venv .venv
  .venv\Scripts\Activate.ps1
  ```

2. Atualizar pip, instalar dependências e checar problemas de dependência
```powershell
pip install --upgrade pip
pip install -r requirements.txt
pip check
```