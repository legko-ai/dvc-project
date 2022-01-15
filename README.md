# dvc-project

Развертывание простого проекта для использования версионирования датасетов на базе DVC.

Варианты развертывания:
- локально
- с использование удаленного хранилища (на примере AWS)

Настройка виртуального окружения:
1. python3 -m venv dvc-project/
2. source dvc-project/bin/activate
3. pip3 install --upgrade pip
4. pip3 install -r requirements.txt
5. python -m ipykernel install --user --name=dvc-project