# Developer notes

## Пояснения 
* Закрытая распродажа реализуется посредством вызова функции mint(адресс кому, адресс сколько токенов c дробной частью в 18 цифры) у контракта токена в любой время до закрытия эмиссии токена
* Установка процента блокировки токенов для token holders кошельков. Для этого необходимо вызвать функцию setVestingPercent(тысячные доли)
* Для спец.кошельков действуют те же правила что и для кошельков инвесторов. Чтобы убрать для них правила нужно вызвать функцию - addAllowedAddress 

## Для продолжения работы необходимо:
* Логотип
* Ссылка на оффициальный сайт