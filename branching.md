[<Назад](./readme.md)

# Ветвление

>**git branch <branch_name>**: создание новой ветки
```
git branch branch_name
```
>**git branch**: просмотр веток
```
git branch
```
>**git checkout**: переключение между ветками
```
git checkout branch_name
```
>**git merge**: слияние репозиториев

1. Переключаемся на основную ветку, которая будет принимать изменения:
   ```
   git checkout main_branch
   ```
2. Сливаем изменения из второстепенной ветки в основную:
   ```
   git merge secondary_branch
   ```
>**git branch -d <branch_name>**: удаление ветки

1. Проверяем текущую ветку:
   ```
   git branch
   ```
2. Переключаемся на основную ветку:
   ```
   git checkout main_branch
   ```
3. Удаляем второстепенную ветку:
   ```
   git branch -d secondary_branch
   ```