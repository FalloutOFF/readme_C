<!-- Ряд кнопок Shield -->
[![MIT License](https://img.shields.io/github/license/FalloutOFF/readme_C?style=for-the-badge)](https://github.com/FalloutOFF/les_HTML5CSS3/search?l=html&type=code)
[![Language](https://img.shields.io/github/languages/count/FalloutOFF/readme_C?style=for-the-badge)](https://github.com/FalloutOFF/les_HTML5CSS3/search?l=html&type=code)
[![Made with](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge&logo=appveyor)](https://www.python.org)

<!-- Логотип проекта -->
<div align="center">
  <img width="80" height="80" src="https://github.com/FalloutOFF/readme_C/blob/main/image/logo.png">

 <h3 align="center">Название проекта</h3><br />
    <a href="https://github.com/github_username/repo_name"><strong>Документация (тех. задание, прототипы)</strong></a>
    <br />
    <a href="https://github.com/github_username/repo_name">Ссылка на приложение</a>
    -
    <a href="https://github.com/github_username/repo_name/issues">Ссылка 1</a>
    -
    <a href="https://github.com/github_username/repo_name/issues">Сссылка 2</a>
 <p align="center">Описание проекта</p>
 </div>
 
 <!-- Оглавление -->
<details>
  <summary>Оглавление</summary>
  <ol>
    <li>
      <a href="#about_p">О проекте</a>
      <ul>
        <li><a href="#built-with">Использовано в проекте</a></li>
      </ul>
    </li>
    <li>
      <a href="#mainScreens">Основные экраны и функции меню</a>
      <ul>
        <li><a href="#mainMenu">Главное меню</a></li>
        <li><a href="#clientProgile">Профиль клиента</a></li>
        <li><a href="#adminProfile">Профиль администратора</a></li>
        <li><a href="#map">Карта</a></li>
      </ul>
    </li>
    <li>
      <a href="#gettingStarted">Установка и инсталяция</a>
      <ul>
        <li><a href="#prerequisites">Предварительные действия</a></li>
        <li><a href="#installation">Установка</a></li>
      </ul>
    </li>
    <li>
      <a href="#backend">Backend</a>
      <ul>
        <li><a href="#python">Python 3.8</a></li>
        <li><a href="#django">Django 3</a></li>
      </ul>
    </li>
        <li>
      <a href="#frontend">Frontend</a>
      <ul>
        <li><a href="#swift">Swift</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- О проекте -->

## <a name="about_p"></a> О проекте

[![Product Screen Shot][Product-Screen-Shot]](https://google.com)

Здесь представляется текстовое описание мобильного приложения. Кратко функционал и что оно делает.

## <a name="built-with"></a>Использовано в проекте

+ [Swift 5](https://developer.apple.com/swift/)
+ [UIKit](https://getuikit.com/)
+ [URLSession](https://developer.apple.com/documentation/foundation/urlsession)
+ [CoreData](https://developer.apple.com/documentation/coredata)
+ [Python 3.8](https://www.python.org/downloads/release/python-380/)
+ [Django 3](https://docs.djangoproject.com/en/4.0/releases/3.0/)

## <a name="mainScreens"></a>Основные экраны и функции меню

### <a name="mainMenu"></a>Главное меню

<div align="center">
  <img width="220" height="420" src="https://github.com/FalloutOFF/readme_C/blob/main/image/scr/main2.PNG">
  <img width="220" height="420" src="https://github.com/FalloutOFF/readme_C/blob/main/image/scr/scr2.PNG">
<div>

### <a name="clientProgile"></a>Профиль клиента

<div align="center">
  <img width="220" height="420" src="https://github.com/FalloutOFF/readme_C/blob/main/image/scr/check.PNG">
</div>

### <a name="adminProgile"></a>Профиль администратора

<div align="center">
  <img width="220" height="420" src="https://github.com/FalloutOFF/readme_C/blob/main/image/scr/mainm.PNG">
</div>

### <a name="map"></a>Карта

<div align="center">
  <img width="220" height="420" src="https://github.com/FalloutOFF/readme_C/blob/main/image/scr/map.PNG">
</div>

## <a name="gettingStarted"></a>Установка и инсталяция


Это пример того, как можно написать инструкцию по настройке проекта.
Чтобы запустить локальную копию, выполните следующие простые шаги.

### <a name="prerequisites"></a>Предварительные действия

Это пример того, как описать инструменты, необходимые для использования программного обеспечения, и как их установить.

* npm
  ```sh
  npm install npm@latest -g
  ```

### <a name="installation"></a>Установка

Ниже приведен пример, как можно описать инструкцию по установке и настройке мобильного приложения.

1. Получите бесплатный ключ API на [https://example.com](https://example.com)
2. Скопируйте хрналище проекта
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Установите NPM-пакеты
   ```sh
   npm install
   ```
4. Введите свой API в `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


## <a name="python"></a>Использование Python 3.8

Пример однострочного Python
```sh
    def __get_random(self, count):
        max_id = self.all().aggregate(max_id=Max("id"))['max_id']  # берем самый большой ID партнера
        pks = set()
```
Пример многострочного Python
```sh
    @classmethod
    def create_or_update(cls, preference: AddressPreferenceModel):
        """
        Изначально проверяем, есть ли в списке этот тип преференции. Если нет, то просто добавляем.
        Если такой тип в списке есть, то нужно пересчитать значения. В списке должны быть только
        минимальные value каждой преференции. То есть, если у одного адреса есть преференция
        Скидка 10%, при этом второму адресу создают Скидка 5%, то в эту таблицу должна попасть Скидка 5%
        Аналогично всем другим преференциям.

        Запрос необходим для отображения значений в списке партнеров. В списке должны отображаться все возможные
        типы преференций со всех адресов партнера, при этом с минимальными значениями value. Если у партнера
        на одном адресе Скидка 5%, а на другом Скидка 10%, то в списке будет отображаться Скидка 5%.

        """
        partner_preference = cls.objects.filter(partner=preference.address.partner,
                                                preference__preference__id=preference.preference.id).first()

        if partner_preference:
            partner_preference.preference = AddressPreferenceModel.objects.filter(
                address__partner=partner_preference.partner,
                preference__id=partner_preference.preference.preference_id).order_by('value').first()
            partner_preference.save()
        else:
            cls.objects.create(partner=preference.address.partner, preference=preference)
```
Django 3
## <a name="django"></a>Использование Django 3
Пример однострочного Django
```sh
from django.db import models
```
Пример многострочного Django
```sh
class Speaker(models.Model):
    name = models.CharField(max_length=32)
    company = models.CharField(max_length=32)
    photo = models.ImageField(upload_to='photos', blank=True, null=True)

    def __unicode__(self):
        return self.name + ' (' + self.company + ')'


class Event(models.Model):
    title = models.CharField(max_length=64)
    speaker = models.ForeignKey(Speaker, blank=False, null=False)
    start_time = models.TimeField()
    end_time = models.TimeField()

    def __unicode__(self):
        return self.title + ' (' + self.speaker.name + ')'
```
## <a name="swift"></a>Использование Swift 5
Пример однострочного Swift
```sh
class TransitionManager: NSObject, UIViewControllerAnimatedTransitioning, UIViewControllerTransitioningDelegate  {
          func animateTransition(transitionContext: UIViewControllerContextTransitioning) {
   }
```
Пример многострочного Swift
```sh
    override func prepareForSegue(segue: UIStoryboardSegue, sender: AnyObject?) {
        // 1
        if segue.identifier == "ppcs" {
            // 2
            if let testPPVC = segue.destinationViewController as? PopVC{
                
                // 3
                if let ppc = testPPVC.popoverPresentationController {
                    ppc.delegate = self
                }
            }
        }
    }
```

________________________________________________________________________________________________
<!-- Ссылка на изображение -->
[Product-Screen-Shot]: image/mp017.png
