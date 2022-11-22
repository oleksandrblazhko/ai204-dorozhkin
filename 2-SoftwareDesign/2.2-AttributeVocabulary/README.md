### Словник атрибутів об’єктів

<table>
    <thead align="center">
        <tr>
            <td>Об'єкт</td>
            <td>Атрибут</td>
            <td>Короткий опис</td>
            <td>Тип</td>
            <td>Обмеження</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="4">User</td>
            <td>ID</td>
            <td>Порядковий номер користувача</td>
            <td>Число</td>
            <td>Значення > 0, індивідуальне значення</td>
        </tr>
        <tr>
            <td>Login</td>
            <td>Логін користувача</td>
            <td>Текст</td>
            <td>Довжина <= 20 символів, індивідуальне значення</td>
        </tr>
        <tr>
            <td>e-mail</td>
            <td>Ел. пошта користувача</td>
            <td>Текст</td>
            <td>Довжина <= 30 символів, індивідуальне значення</td>
        </tr>
        <tr>
            <td>Age</td>
            <td>Вік користувача</td>
            <td>Число</td>
            <td>Значення > 0</td>
        </tr>
        <tr>
            <td rowspan="4">Food</td>
            <td>ID</td>
            <td>Порядковий номер картки їжі</td>
            <td>Число</td>
            <td>Значення > 0, індивідуальне значення</td>
        </tr>
        <tr>
            <td>Name</td>
            <td>Логін користувача</td>
            <td>Текст</td>
            <td>Довжина <= 20 символів, індивідуальне значення</td>
        </tr>
        <tr>
            <td>Cost</td>
            <td>Кошттовність продукту</td>
            <td>Число</td>
            <td>Значення > 0</td>
        </tr>
        <tr>
            <td>Weight</td>
            <td>Вага продукту</td>
            <td>Число</td>
            <td>Значення > 0</td>
        </tr>
        <tr>
            <td rowspan="4">Physical exercise</td>
            <td>ID</td>
            <td>Порядковий номер вправи</td>
            <td>Число</td>
            <td>Значення > 0, індивідуальне значення</td>
        </tr>
        <tr>
            <td>Description</td>
            <td>Короткий опис вправи</td>
            <td>Текст</td>
            <td>Довжина <= 300 символів</td>
        </tr>
        <tr>
            <td>Complexity</td>
            <td>Складність виконання</td>
            <td>Число</td>
            <td>Значення від 0 до 5</td>
        </tr>
        <tr>
            <td>Attachments</td>
            <td>Місце для посилань на додатковий матеріал</td>
            <td>Текст</td>
            <td>Довжина <= 500 символів</td>
        </tr>
        <tr>
            <td rowspan="3">Filter</td>
            <td>Weight</td>
            <td>Максимальна додаткова вага</td>
            <td>Число</td>
            <td>Значення > 0</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>Максимальний час тренування</td>
            <td>Число</td>
            <td>Значення > 0</td>
        </tr>
        <tr>
            <td>Skill</td>
            <td>Максимальна пошукова складність</td>
            <td>Число</td>
            <td>Значення від 0 до 5</td>
        </tr>
        <tr>
            <td rowspan="2">List of exercises</td>
            <td>ID</td>
            <td>Логін творця списку</td>
            <td>Текст</td>
            <td>Довжина <= 20 символів</td>
        </tr>
        <tr>
            <td>Description</td>
            <td>Короткий опис комплексу вправ</td>
            <td>Текст</td>
            <td>Довжина <= 300 символів</td>
        </tr>
        <tr>
            <td rowspan="2">Basket</td>
            <td>Total cost</td>
            <td>Сума продуктів у кошику</td>
            <td>Число</td>
            <td>Значення < 100000</td>
        </tr>
        <tr>
            <td>Condition</td>
            <td>Статус набору</td>
            <td>Текст</td>
            <td>Довжина <= 50 символів</td>
        </tr>
</table>
