# hse24_hw6
### Иллерицкий Павел Александрович

[Colab](https://colab.research.google.com/drive/1z-QWQ8YTYXtWpc8bcUR57elaoj4Ibrnc?usp=sharing)

## Анализ QC прочтений
Данные отчета FasQC приведены для файла SRR5836473_1 что соответствует этапу 8cell. зависимости:

Наблюдается резкое падение качества чтений ближе к концу.
![image](https://github.com/user-attachments/assets/12ada7dd-22d1-444d-8aec-72d544891ada)


Расхождение между тимином и цитазином, должно быть примерно равно.
![image](https://github.com/user-attachments/assets/e927f3b1-b87e-4b16-a739-b7fd6da3bd86)


Выраженное отклонение от теории в распределении.
![image](https://github.com/user-attachments/assets/65ebfb17-c24b-4576-8dd8-83c5a45d0ac6)


## Риды
BS-Seq | 11347700-11367700 | 40185800-40195800 | deduplication 
--- | --- | --- | ---
SRR5836473 | 551  | 194 | 81.72%
SRR3824222 | 1344 | 565 | 97.09%
SRR5836475 | 797  | 274 | 90.93%

## Рисунки с уровнем метилирования и покрытием

#### SRR5836473 - 8 Cell
![image](https://github.com/user-attachments/assets/7afbe728-8e78-42f1-aef5-d7042574bd7b)

#### SRR5836475 - ICM
![image](https://github.com/user-attachments/assets/bb322731-a5c6-4986-82e7-d52f6f8360fe)


#### SRR3824222 - Epiblast
![image](https://github.com/user-attachments/assets/3a4a0e25-6b8b-40a1-a4d3-d6d6a338c3b6)

На графиках видно, что 8 cell имеет уровень CpG-метилирования около 43–44%, ICM – значительно ниже, примерно 22–23%, а Epiblast – самый высокий, около 78–79%. Эти данные соответствуют статье. Во втором риде наблюдается небольшой смещение. Кроме того, полученные значения немного расходятся с ожидаемыми: на ранних стадиях метилирование CpG снижается до ~25%, а потом при дифференцировке тканей резко возрастает до ~90%.

## Гистограмы распределения метелирования цитозинов по хромосоме
![image](https://github.com/user-attachments/assets/a26987e5-9f88-477b-9a97-2c14acdae2ea)
![image](https://github.com/user-attachments/assets/1e017e14-c8e9-488a-b545-146ee6a7e42b)
![image](https://github.com/user-attachments/assets/e8bcb026-ce42-4c59-aa11-cf0213b20dcc)

Гистограммы как и ожидалось отражают теорию.

## Уровень метилирования и покрытия

Метилирование
![image_meth](https://github.com/user-attachments/assets/061a98de-141f-4454-86ba-4a32a648ebf8)

Покрытие
![image_cov](https://github.com/user-attachments/assets/7e4d26fd-9a79-4940-bc22-d4bba88ae2dc)

## DMC/DMR 
смотрите коллаб

## ДОП
Пересечения с генами можно посмотреть в data/dmr/. Замечание количество генов в пересечении меньше общего количества генов, как и должно быть.

### Онтология
8cell-icm
![image](https://github.com/user-attachments/assets/ac1b9dec-bdfd-4cef-9a81-1b7c49a707b9)

icm-epiblast
![image](https://github.com/user-attachments/assets/649eefe1-0837-40e6-b656-93730443cdfd)

8cell-epiblast
![image](https://github.com/user-attachments/assets/29d0bc5c-beac-4c2a-9b78-3699ba1d6776)
