# 🚀 Git Branch Cheat Sheet

```bash
# 🌱 СОЗДАТЬ ВЕТКУ:
git branch feature_123              # Создать ветку
git checkout -b feature_123         # Создать и переключиться (старый способ)
git switch -c feature_123           # Создать и переключиться (новый способ)

# 🔀 ПЕРЕКЛЮЧИТЬСЯ МЕЖДУ ВЕТКАМИ:
git checkout main                   # Переключиться (старый способ)
git switch main                     # Переключиться (новый способ)
git branch                          # Показать локальные ветки
git branch -a                       # Показать ВСЕ ветки (включая удалённые)

# 📤 ОТПРАВИТЬ ВЕТКУ НА СЕРВЕР:
git push -u origin feature_123      # Первая отправка (с привязкой)
git push                            # Отправить изменения (после привязки)
git push origin feature_123         # Явная отправка в определённую ветку

# 🗑 УДАЛИТЬ ВЕТКУ:
git branch -d feature_123           # Удалить локальную ветку
git push origin --delete feature_123 # Удалить удалённую ветку