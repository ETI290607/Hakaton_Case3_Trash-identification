# Кейс №3: Автоматическая сортировка мусора 
Команда: ГБОУ Школа 258-2 <br>
Школа: ГБОУ Школа №258 <br>
Участники:<br>
-Ильин Егор<br> 
-Пашков Владислав<br> 
-Королев Даниил <br>
***
# Инсталляция и запуск:
1) Необходио по гиперссылкам установить дистрибутив [Anaconda](https://www.anaconda.com/download/success), программно-аппаратную архитектуру [CUDAv1.18](https://developer.nvidia.com/cuda-11-8-0-download-archive) и пакет PyTorch следующей командой в приложении Anaconda Prompt:<br>
```console
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```
2) Открыть Anaconda Navigator, перейти в менеджер виртуальных сред (кнопка Environments), запустить среду Base (root) (нажать на кнопку, в открывшемся меню нажать "Open with Python").<br>
3) В открывшемся окне надо установить необходимые пакеты следующей командой: <br>
```console
conda install -c pytorch -c nvidia -c conda-forge pytorch torchvision pytorch-cuda=11.8 ultralytics
```
