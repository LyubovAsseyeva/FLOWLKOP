---
description: >-
  После установки КриптоПро и Сертификата ГУЦ необходимо установить КриптоАРМ,
  именно в этом модуле проходит подписание документов.
---

# КриптоАРМ

Подробнее об установке модуля Крипто АРМ

Перейдите на сайт [https://cryptoarm.ru/cryptoarm-5/](https://cryptoarm.ru/cryptoarm-5/)  и приобретите модуль КриптоАРМ.

## Установка КриптоАРМ 5

1. После запуска  выбрать "Настраиваемая установка", затем "Далее".

<figure><img src="../../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure>

2. Выбрать для "КриптоАРМ" вариант «Этот компонент и его подкомпоненты будут установлены на локальный жесткий диск» и нажать "Далее".

<figure><img src="../../.gitbook/assets/telegram-cloud-photo-size-2-5197425193331575013-y.jpg" alt=""><figcaption></figcaption></figure>

3. Ознакомиться и принять "Лицензионное соглашение".

<figure><img src="../../.gitbook/assets/telegram-cloud-photo-size-2-5197425193331575014-y.jpg" alt=""><figcaption></figcaption></figure>

&#x20;4\. После установки нажать "Готово".

<figure><img src="../../.gitbook/assets/telegram-cloud-photo-size-2-5197425193331575017-x.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**После завершения установки необходимо перезагрузить компьютер.**&#x20;
{% endhint %}

## Настройка КриптоАРМ _(10 шагов и вы у цели!)_

1. Открыть КриптоАРМ (Для КриптоАРМ на рабочем столе будет создан ярлык, необходимо кликнуть по нему).

&#x20;\


<figure><img src="../../.gitbook/assets/telegram-cloud-photo-size-2-5197425193331575022-x (1).jpg" alt=""><figcaption></figcaption></figure>

2. &#x20; В пункте меню "Помощь" установить лицензию.

<figure><img src="../../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>

3. Прописать лицензионные ключи и нажать "Ок".&#x20;
4. Выбрать в меню КриптоАРМ "Профили" - "Управление профилями" -"Создать".

<figure><img src="../../.gitbook/assets/telegram-cloud-photo-size-2-5197425193331575027-y.jpg" alt=""><figcaption></figcaption></figure>

5\. В пункте «Общие» прописать имя профиля и указать сертификат пользователя с помощью кнопки «Выбрать».



<figure><img src="../../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

6. В пункте "Подпись" установить формат подписи на "Усовершенствованная".&#x20;

{% hint style="danger" %}
**Для создания открепленной подписи установить галочку "Сохранять подпись в отдельном файле" (без установленной галочки будет создаваться прикрепленная подпись).**
{% endhint %}

<figure><img src="../../.gitbook/assets/telegram-cloud-photo-size-2-5197425193331575032-y.jpg" alt=""><figcaption></figcaption></figure>

7. В пункте "TSP" в поле "Адрес службы штампов времени" указать адрес службы штампов времени (например, [http://tax4.tensor.ru/tsp/tsp.srf](http://tax4.tensor.ru/tsp/tsp.srf)).

<figure><img src="../../.gitbook/assets/image (139).png" alt=""><figcaption></figcaption></figure>

8.  В пункте "OCSP" в поле "Адрес сервера" необходимо указать адрес OCSP сервера, указанный указан в свойствах сертификата пользователя.

    1. Открыть Certificates через меню Пуск.
    2. Выбрать пункт "Доступ к информации о центрах сертификации"/Authority Information Access.
    3.  Скопировать URL.&#x20;

        <figure><img src="../../.gitbook/assets/image (127).png" alt=""><figcaption></figcaption></figure>
    4. Вставить полученный URL&#x20;



    <figure><img src="../../.gitbook/assets/image (123) (1).png" alt=""><figcaption></figcaption></figure>
9. Выбрать в пункте "Профили" созданный профиль "По умолчанию".

<figure><img src="../../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

10. Выполнить настройку в пункте "Режимы" (по желанию - необязательное условие).

<figure><img src="../../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

**Настройка завершена. Поздравляем!**\


## Подробнее о подписании документа

{% hint style="danger" %}
Во время подписания на компьютере должен быть доступ к электронной подписи. То есть, если она на USB-накопителе, то он должен быть вставлен в компьютер.
{% endhint %}

1. Открыть установленный КриптоАРМ (ярлык на рабочем столе).
2. Нажать "Подписать".
3. Выбрать файл для подписи.

<figure><img src="../../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>

4. Ввести пин-код вашей Электронной подписи и нажмите "ОК".

<figure><img src="../../.gitbook/assets/telegram-cloud-photo-size-2-5199676993145259340-x.jpg" alt=""><figcaption></figcaption></figure>

В каталоге на компьютере будет 2 файла:&#x20;

* сам документ;
* файл с открепленной подписью в формате sig.

&#x20;Файла с открепленной подписью в формате SIG необходимо загрузить во Flow.

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Итоговый документ - бланк документа и два файла в формате SIG&
{% endhint %}
