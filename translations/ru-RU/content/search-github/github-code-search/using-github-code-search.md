---
title: Использование GitHub Code Search (бета-версия)
intro: 'Вы можете использовать предложения, завершения и сохраненные поисковые запросы в обновленном интерфейсе поиска, чтобы быстро найти то, что вы ищете в {% data variables.product.prodname_dotcom_the_website %}.'
allowTitleToDifferFromFilename: true
versions:
  feature: github-code-search
topics:
  - GitHub search
ms.openlocfilehash: 7578dd05f251b1df23fbd64c63d04e533f7fa9ef
ms.sourcegitcommit: e8c012864f13f9146e53fcb0699e2928c949ffa8
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/09/2022
ms.locfileid: '148160200'
---
{% note %}

**Примечание.** {% data reusables.search.code-search-code-view-beta-note %}

{% data reusables.search.code-search-link %} {% data reusables.search.code-view-link %}

{% endnote %}

## Сведения об использовании нового поиска кода (бета-версия)

Получив доступ к новой бета-версии поиска кода, GitHub будет индексировать все репозитории, которые у вас есть, и все репозитории в организациях, в которых вы являетесь участником, как общедоступные, частные, так и внутренние. Это означает, что вы можете выполнять поиск по всем репозиториям, а также общедоступным репозиториям в {% data variables.product.prodname_dotcom_the_website %}, которые уже проиндексированы. Только пользователи, имеющие разрешение на просмотр кода в {% data variables.product.prodname_dotcom_the_website %}, смогут видеть ваш код в результатах поиска. Вилки индексируются и доступны для поиска так же, как и другие репозитории.

Не весь код индексируется, и в настоящее время можно выполнять поиск только ветвях репозиториев по умолчанию. Дополнительные сведения об известных ограничениях см. в разделе [Сведения о поиске кода GitHub (бета-версия)](/search-github/github-code-search/about-github-code-search#limitations)".

Новая бета-версия поиска кода интегрирована в бета-версию нового представления кода. {% data reusables.search.code-view-link %}

## Использование строки поиска

На вершине новой системы поиска кода бета-версия включает обновленный интерфейс поиска в {% data variables.product.prodname_dotcom_the_website %}. Используя предложения, завершения и сохраненные поисковые запросы, вы можете быстро найти нужные данные, часто не вводя полный запрос или просматривая страницу результатов поиска.

Дополнительные сведения о синтаксисе поиска нового кода (бета-версия) см. в разделе [Основные сведения о синтаксисе поиска кода GitHub (бета-версия).](/search-github/github-code-search/understanding-github-code-search-syntax)

{% data reusables.search.non-code-search-explanation %}

1. В верхней области навигации {% data variables.product.prodname_dotcom_the_website %} щелкните строку поиска.
1. В строке поиска вы увидите список предложений, упорядоченных по категориям, включая последние поисковые запросы и рекомендуемые репозитории, команды и проекты, к которым у вас есть доступ. Вы также можете просмотреть список сохраненных поисковых запросов, которые вы создали. Дополнительные сведения о сохраненных поисках см. в разделе [Создание сохраненных поисковых запросов и управление ими](#creating-and-managing-saved-searches).

    ![Панель поиска с предложениями и сохраненными поисковыми запросами](/assets/images/help/search/code-search-beta-search-bar.png)

    Если щелкнуть какое-либо из конкретных предложений, вы перейдете непосредственно на страницу этого предложения (например, на страницу репозитория или проекта). Если щелкнуть недавний или сохраненный поиск, в зависимости от типа поиска поисковый запрос появится в строке поиска или вы перейдете на страницу результатов поиска для условия поиска.

1. После ввода поискового запроса вы увидите список завершений и предложений, которые соответствуют вашему запросу. Вы можете щелкнуть предложение, чтобы перейти к определенному расположению. При вводе дополнительных квалификаторов вы увидите более конкретные предложения, например файлы кода, к которые можно перейти напрямую.
   
   ![Панель поиска с запросом и предложениями кода](/assets/images/help/search/code-search-beta-search-bar-code-suggestions.png)

1.  После ввода запроса можно также нажать клавишу ВВОД, чтобы перейти к полному представлению результатов поиска, где можно просмотреть каждое совпадение и визуальный интерфейс для применения фильтров. Дополнительные сведения см. в разделе [Использование представления результатов поиска](#using-the-search-results-view).

## Создание сохраненных поисковых запросов и управление ими

1. В верхней области навигации {% data variables.product.prodname_dotcom_the_website %} щелкните строку поиска и начните вводить поисковый запрос (или любую букву).
1. В строке поиска должен появиться раздел "Сохраненные поисковые запросы". Щелкните {% octicon "plus-circle" aria-label="The plus-circle icon" %} **Создать сохраненный поиск**.

    ![Кнопка "Создать сохраненный поиск" в строке поиска](/assets/images/help/search/code-search-beta-create-saved-search.png)

1. Во всплывающем окне укажите имя запроса и запрос, который требуется сохранить. Щелкните **Создать сохраненный поиск**.

    ![Окно "Создание сохраненного поиска"](/assets/images/help/search/code-search-beta-create-saved-search-window.png)

1. Если снова щелкнуть строку поиска, вы увидите сохраненный поиск в разделе "Сохраненные поисковые запросы" в строке поиска. Если щелкнуть сохраненную запись поиска, запрос будет добавлен в строку поиска и соответствующим образом отфильтрованы предложения.

  ![Использование сохраненного поиска в строке поиска](/assets/images/help/search/code-search-beta-saved-search-in-search-bar.png)

    - Чтобы изменить сохраненный поиск, в разделе "Сохраненные поисковые запросы" щелкните {% octicon "pencil" aria-label="The pencil icon" %} справа от сохраненного поиска. 
    - Чтобы удалить сохраненный поиск, щелкните {% octicon "trash" aria-label="The trash icon" %} справа от сохраненного поиска.

  ![Кнопки для изменения или удаления сохраненного поиска](/assets/images/help/search/code-search-beta-edit-or-delete-saved-search.png)

## Использование представления результатов поиска

Представление результатов поиска уже существует для классического поиска на GitHub, и функции для большинства типов поиска, за исключением кода, одинаковы. После включения новой бета-версии поиска по коду страница результатов поиска имеет переработанный пользовательский интерфейс и включает фильтры, которые поддерживаются в новой поисковой системе кода, такие как фильтры пути и символов.

Чтобы создать поисковый запрос, а также просмотреть и отфильтровать результаты с помощью визуального интерфейса, можно использовать {% data variables.search.search_page_url %} или {% data variables.search.advanced_url %}. Если нажать клавишу ВВОД после ввода поискового запроса в строке поиска, вы также перейдете в представление результатов поиска.

В представлении результатов поиска можно переходить между различными типами результатов поиска, включая код, проблемы, запрос на вытягивание, репозитории и многое другое. Вы также можете просматривать и использовать фильтры.

![Представление результатов поиска](/assets/images/help/search/code-search-beta-results-view.png)