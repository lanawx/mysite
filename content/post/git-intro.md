---
title: "Введение в Git"
date: 2026-03-16
authors:
  - admin
tags:
  - git
---

## Что такое Git?

Git — это распределенная система управления версиями, которая помогает отслеживать изменения в коде и координировать работу нескольких разработчиков.

## Основные понятия

### Репозиторий
Хранилище вашего проекта и всей истории изменений.

### Коммит (commit)
Снимок состояния проекта на определенный момент времени.

### Ветка (branch)
Отдельная линия разработки, позволяющая работать над новыми функциями независимо.

## Основные команды

```bash
# Настройка Git
git config --global user.name "Ваше Имя"
git config --global user.email "ваш.email@example.com"

# Создание репозитория
git init
git clone https://github.com/username/repo.git

# Ежедневная работа
git status                    # Проверка состояния
git add filename.txt          # Добавление файла
git add .                     # Добавление всех изменений
git commit -m "Сообщение"     # Сохранение изменений
git push origin main          # Отправка на сервер
git pull origin main          # Получение обновлений

# Ветвление
git branch new-feature        # Создание ветки
git checkout new-feature      # Переключение на ветку
git merge new-feature         # Слияние веток
```
