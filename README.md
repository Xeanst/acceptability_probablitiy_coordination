Репозиторий с материалами для статьи "Взаимосвязь между приемлемостью и вероятностью высказываний: данные предикативного согласования с сочиненным подлежащим в русском языке"

**Аннотация**: Данное исследование нацелено установить, способны ли языковые модели, обученные на неразмеченных текстовых данных, моделировать согласовательную вариативность. Мы провели сравнение суждений о приемлемости, вынесенных носителями языка, и вероятностных метрик, предсказанных двунаправленной языковой моделью ruBERT в базовой конфигурации без тонкой настройки. В качестве лингвистического феномена рассматривалось предикативное согласование с сочиненным подлежащим в русском языке. Мы подробно проанализировали, какие синтаксические, морфологические и семантические факторы оказывают влияние на приемлемость и вероятность высказываний. Использование результатов синтаксических экспериментов позволило выявить роль каждого фактора по отдельности, а также их взаимодействия. Помимо стандартной метрики для оценки вероятности последовательности, использовались ее вариации, учитывающие либо длину последовательности, либо вероятность каждого токена, либо оба этих параметра. Мы предполагали, что модель будет предсказывать наибольшую вероятность той стратегии, которая является наиболее приемлемой с точки зрения носителей языка. Однако данная гипотеза не подтвердилась: наличие вариативного согласования с сочиненным подлежащим снижает корреляцию между приемлемостью и вероятностью. Линейное расположение элементов предложения – позиция подлежащего и сказуемого, порядок конъюнктов – оказалось единственным фактором, который в равной степени оказывает влияние на приемлемость и вероятность высказывания. Совпадение рода конъюнктов повышает приемлемость предикативного согласования по единственному числу, однако не меняет его вероятность. Одушевленность конъюнктов и симметричность предиката не влияют ни на приемлемость, ни на вероятность высказывания. Наше исследование показывает, что рассматриваемая языковая модель без тонкой настройки не может быть использована для моделирования предикативного согласования с сочиненным подлежащим. Приемлемость высказывания опирается на более тонкие языковые контрасты, которые не значимы при автоматической оценке его вероятности.

Репозиторий содержит набор данных **PredAgrCoord**, который используется в статье для проведения экспериментов.
