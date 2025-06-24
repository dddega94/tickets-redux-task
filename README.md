# Вам предстоит создать приложение для поиска авиабилетов с помощью React, Redux Toolkit и TypeScript.




## Особенности приложения:


* Работа с фейковым серверным API с помощью async-thunk
* Сортировка билетов по цене, длительности перелёта и количеству пересадок
* Фильтрация по авиакомпаниям
* Фильтрация по количеству пересадок


### Вы можете использовать любой формат данных, но он должен поддерживать сортировку.

Пример сущности, приходящей из API эталонного задания:

    export interface TicketTime {
        startTime: string;
        endTime: string;
    }

    export interface Ticket {
        id: number;
        from: string;
        to: string;
        company: string;
        price: number;
        currency: 'RUB';
        time: TicketTime;
        duration: number;
        date: string;
        connectionAmount: number | null;
    }

    
Чтобы создать заготовку проекта, воспользуйтесь Vite и выберите пресет react-ts или react-swc-ts:

npm create vite@latest или yarn create vite

Также вы можете использовать Create React App (но учтите, что с сентября 2022 г. эта утилита больше не поддерживается).

