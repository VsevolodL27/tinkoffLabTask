# tinkoffLabTask
TLab.NLP Тестовое 23Q4 - тестовое задание в Лабораторию Тинькофф
Проект состоит из 2 частей:
1. Level 1 - задача заключалась в том, чтобы сгенерировать N выходов с помощью SFT модели, составить пары winner-loser, где winner — выход модели с большим ревардом, обучить модель с hinge и sigmoid лоссами, провести сравнения полученных результатов. Метрики находятся: https://api.wandb.ai/links/lavrenov-vv/8a9rt3du.
2. Level 2 - цель расширить метод dpo_loss функциями потерь из статьи https://arxiv.org/pdf/2309.16240v1.pdf, обучить модель на этих функциях потерь, построить график приведенный в статье. Метрики находятся: https://wandb.ai/lavrenov-vv/uncategorized/reports/Level-2--Vmlldzo2MjMyNDE4.
   
Чтобы запустить блокнот его нужно запустить в виртуальной среде с библиотеками, указанными в requirements.txt. Для запуска Level 2 предварительно необходимо скачать файл prompt_chosen_rejected_dict.pkl в директорию c блокнотом. При запуске в colab, kaggle библиотеки из requirements.txt устанавливать необязательно.
