# Chinese-Alchemy-Generator

Предпринятые действия:
- Собрал датасет через сайт [Chinese Text Project](https://ctext.org/)
- Очистил собранные данные, разделил на трейновую и тестовую выборки
- Создал 2 модели на базе предтренированных моделей [Chinese Poem](https://huggingface.co/uer/gpt2-chinese-poem) 
- Определил количество эпох, длины последовательностей и размер бачей, задал оптимизатор и метрику
- Обучил модель
- При помощи предобученной модели [Helsinki NLP](https://huggingface.co/Helsinki-NLP/opus-mt-zh-en) сделал переводчик
