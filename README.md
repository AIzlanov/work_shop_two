# 🛒 ML Sales Prediction — Документация
## Описание проекта
Этот проект реализует модель, которая предсказывает вероятность покупки в течение 90 дней.  
С её помощью мы выделяем пользователей, которые готовы совершить покупку в ближайшее время   
для интернет-магазина, который оптимизирует процесс планирования будущих продаж.   

## Структура проекта
Workshop-2/  
│  
├── data/  
│   └── apparel_messages.csv  
│   └── apparel-purchases.csv  
│   └── apparel-target_binary.csv  
│   └── full_campaign_daily_event.csv (опциональный)  
│   └── full_campaign_daily_event_channel.csv (опциональный)  
│  
├── requirements.txt (сведения о необходимых библиотеках)    
├── research.ipynb (тетрадка с исследованием)  
└── README.md  (описание проекта)

## Установка
0. Скачать файлы: 
- apparel_messages.csv [скачать](https://drive.google.com/file/d/18VXr3S3FXi2RovLPaGQV_cRqndkH-WlZ/view?usp=drive_link)
- apparel-purchases.csv [скачать](https://drive.google.com/file/d/1UhYjOwEiwZbfQux4Lak3BC6riA8WYCpy/view?usp=drive_link)
- apparel-target_binary.csv [скачать](https://drive.google.com/file/d/1v6hMdAVjRCNrJjceKTlIM1-SrX1WMDcl/view?usp=drive_link)
- full_campaign_daily_event.csv [скачать](https://drive.google.com/file/d/1erEqAOLin_BjzcTAc-A_XXOMeuhJ6Xeb/view?usp=drive_link)
- full_campaign_daily_event_channel.csv [скачать](https://drive.google.com/file/d/19lOaCDo3hD-PEp3zChD2iqwcRJh_7hju/view?usp=drive_link)

1. Клонирование проекта  
```bash
git clone https://github.com/AIzlanov/work_shop_two.git
```    

3. Установка зависимостей
```bash
pip install -r requirements.txt
```

## Заключение
В рамках этого проекта были реализованы следующий шаги:   
- разработана модель для предсказания клиентов, которые совершат покупку   
- написана пользовательская и техническая документация   