# Чайка-сервис — демо-сайт

> **Демо-версия.** Это прототип, а не официальный сайт организации. Он будет удалён по первой просьбе владельца. Данные и фото взяты из публичной карточки на Яндекс Картах (23.11.2026), права на них принадлежат владельцам.

- Организация: Чайка-сервис, Барановичи, ул. Бадака, 15
- Карточка: https://yandex.by/maps/-/CXc6Y6PB
- Дизайн: премиальный минимализм (светлая или тёмная тема, подстраивается под систему)
- Сайт: один файл `index.html`, чистые HTML/CSS/JS без сборки (только шрифт Inter с Google Fonts)
- Данные карточки: `data.json`; фото подгружаются ссылками с серверов Яндекса

## Публикация на GitHub Pages

```bash
git init && git add . && git commit -m "Демо-сайт Чайка-сервис"
git branch -M main
git remote add origin https://github.com/<user>/chayka-servis.git
git push -u origin main
```

Затем: Settings → Pages → Deploy from a branch → `main` / `(root)`.
Адрес: `https://<user>.github.io/chayka-servis/`
