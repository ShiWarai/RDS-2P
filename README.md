# RDS-2P

[![ROS 2 Humble](https://img.shields.io/badge/ROS%202-Humble-22314E?style=flat&logo=ros&logoColor=white)](https://docs.ros.org/en/humble/)

Репозиторий‑хаб проекта **RDS‑2P** (robot dog small, версия 2, пластиковая).
Проект робота-квадрупеда для сборки дома или в учебном учреждении в условиях ограниченных средств, но большого желания. Основной упор сделан на дешёвые компоненты и функциональность, с небольшим заделом на замещение зарубежных компонентов конкурентными отечественными решениями.

Управление системой робота происходит через ROS 2 Humble. Дополнительные методы и способы взаимодействия описаны в репозитории RDS-2P-software.

<img width="960" height="544" alt="image" src="https://github.com/user-attachments/assets/7c9a9a3c-b5e2-4c6b-8d09-092c78efe3b1" />

## Медиа

- **Симуляция (mp4)**: [`media/sim_walk.mp4`](media/sim_walk.mp4)
- **Реальная ходьба (mp4)**: [`media/real_walk.mp4`](media/real_walk.mp4)

Если хочется именно встроенный плеер в `README.md`, обычно GitHub отображает его только для видео, загруженных как *attachments* (ссылка вида `https://github.com/user-attachments/assets/...`). Тогда можно вставить так:

```html
<video src="https://github.com/user-attachments/assets/UUID" controls muted playsinline></video>
```

## Репозитории проекта

| Репозиторий | Назначение | Статус |
|---|---|---|
| [`RDS-2P-blueprint`](https://github.com/ShiWarai/RDS-2P-blueprint) | Чертежи робота | public |
| [`RDS-2P-circuits`](https://github.com/ShiWarai/RDS-2P-circuits) | Электросхемы робота | public |
| [`RDS-2P-software`](https://github.com/ShiWarai/RDS-2P-software) | ROS2 пакеты и прочий софт для робота | public |
| [`RDS-2P-Salute`](https://github.com/ShiWarai/RDS-2P-Salute) | Навык для голосового помощника Сбер Салют | public |
| [`CVC`](https://github.com/ShiWarai/CVC) | Классификатор голосовых команд робота, используется вместе с RDS-2P-Salute | public |
| [`RDS-2P-simulator`](https://github.com/ShiWarai/RDS-2P-simulator) | Обучение робота в Mujoco, с использованием параметризированногог пайплайна обучение PPO | private |
