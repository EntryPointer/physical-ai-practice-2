# Практика 2 — настройка обучения PandaPickCube (RSL-RL PPO)

Публичный репозиторий для проверки.

## Структура

- `model/` — чекпоинты и логи пяти экспериментов:
  - `baseline`
  - `box_target_strong`
  - `qpos_strong`
  - `num_envs_2048`
  - `no_floor_x10`
- `videos/` — видео инференса (10 эпизодов) по каждому эксперименту
- `отчет.pdf` — гипотезы, таблица, кривые, выводы

## Условия обучения

- CPU (Docker, Apple M4)
- seed=42, max_iters=1001
- baseline `num_envs=1024`
