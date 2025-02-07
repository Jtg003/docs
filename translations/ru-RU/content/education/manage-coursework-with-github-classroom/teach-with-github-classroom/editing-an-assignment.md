---
title: Изменение задания
intro: Вы можете изменить существующие задания в курсе.
versions:
  fpt: '*'
permissions: 'Organization owners who are admins for a classroom can edit assignments for that classroom. {% data reusables.classroom.classroom-admins-link %}'
shortTitle: Edit an assignment
ms.openlocfilehash: 65814debd3fb5bf64ea83b04bef6349b7755b77f
ms.sourcegitcommit: 82b1242de02ecc4bdec02a5b6d11568fb2deb1aa
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/21/2022
ms.locfileid: '148179859'
---
## Сведения о редактировании заданий

После создания задания можно изменить многие аспекты задания в соответствии с потребностями себя и учащихся. Имейте в виду, что после создания назначения нельзя изменить тип назначения (отдельный или групповой) или интегрированную среду разработки (IDE). Дополнительные сведения см. в разделах [Создание отдельного назначения](/education/manage-coursework-with-github-classroom/teach-with-github-classroom/create-an-individual-assignment) и [Создание группового назначения](/education/manage-coursework-with-github-classroom/teach-with-github-classroom/create-a-group-assignment).

## Изменение существующего назначения

1. Войдите в {% data variables.product.prodname_classroom_with_url %}.
1. Перейдите к аудитории.

    ![Снимок экрана: плитка аудитории в GitHub Education с выделенным именем аудитории](/assets/images/help/classroom/classroom-card.png)

1. На вкладке {% octicon "repo" aria-label="The repo icon" %} **Задания** рядом с заданием, который вы хотите изменить, щелкните {% octicon "pencil" aria-label="Значок карандаша" %}.

    {% note %}
    
    **Примечание:** Вы также можете изменить задание на странице назначения. Чтобы открыть страницу назначения, на вкладке **Назначения** щелкните имя назначения.
    
    {% endnote %}

    ![Снимок экрана: задание с акцентом на значке редактирования](/assets/images/help/classroom/edit-assignment.png)

1. В разделе "Название назначения" щелкните текстовое поле, а затем удалите существующий текст и введите новое название назначения.

    ![Снимок экрана: редактор заданий с акцентом на текстовом поле "Название назначения"](/assets/images/help/classroom/edit-assignment-title.png)

1. При необходимости, чтобы изменить префикс по умолчанию для репозитория заданий каждого учащегося, щелкните {% octicon "pencil" aria-label="The pencil icon" %}.

    {% note %}

    **Примечание:** Изменение заголовка назначения или префикса репозитория по умолчанию не приведет к изменению имени существующих репозиториев назначений.

    {% endnote %}

    ![Снимок экрана: редактор заданий с акцентом на значке редактирования для префиксов репозитория учащихся](/assets/images/help/classroom/edit-assignment-repository-prefix-icon.png)

    Затем введите новый префикс в разделе "Префикс пользовательского репозитория".

    ![Снимок экрана: редактор назначений с акцентом на текстовом поле "Настраиваемый префикс репозитория"](/assets/images/help/classroom/edit-assignment-repository-prefix.png)

1. В разделе "Крайний срок (необязательно)" щелкните текстовое поле, а затем используйте средство выбора даты, чтобы переназначить крайний срок. Новый крайний срок не может быть в прошлом, и переназначение крайнего срока обновит крайний срок для всех учащихся.

    ![Снимок экрана: редактор назначений с акцентом на поле "Крайний срок (необязательно)"](/assets/images/help/classroom/edit-assignment-deadline.png)

1. Чтобы изменить состояние назначения, выберите раскрывающееся меню **Состояние назначения** и выберите **активный** или **неактивный**.

    {% note %}
  
    **Примечание:** Неактивные задания не могут быть приняты учащимися. Вы должны изменить состояние задания на неактивным, когда учащиеся больше не примут задание или срок задания истек.
  
    {% endnote %}

    ![Снимок экрана: редактор назначений с акцентом на раскрывающемся меню "Состояние назначения"](/assets/images/help/classroom/edit-assignment-status-dropdown.png)

1.  В разделе "Видимость репозитория" выберите видимость. Если вы используете частные репозитории, то ваш отзыв смогут увидеть только учащийся или команда.

    {% note %}
    
    **Примечание:** Изменение видимости для репозиториев назначений не приведет к ретроактивным изменениям видимости существующих репозиториев назначений.
    
    {% endnote %}

    ![Снимок экрана: редактор назначений с акцентом на переключателях "Видимость репозитория"](/assets/images/help/classroom/edit-assignment-repository-visibility.png)

1.  При необходимости выберите или снимите флажок **Предоставить учащимся доступ администратора к репозиторию**. Дополнительные сведения о разрешениях администратора для репозиториев см. в разделах [Сведения о репозиториях](/repositories/creating-and-managing-repositories/about-repositories#about-repository-visibility) и Роли [репозитория для организации](/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization).

    {% note %}

    **Примечание:** Предоставление или отмена доступа администратора учащихся после создания задания не приведет к обратному изменению разрешений для существующих репозиториев заданий.

    {% endnote %}

    ![Снимок экрана: редактор заданий с акцентом на флажок "Предоставить учащимся доступ администратора к репозиторию"](/assets/images/help/classroom/edit-assignment-admin-access.png)

1. Чтобы настроить или изменить репозиторий шаблонов для задания, в разделе "Добавление репозитория шаблонов для предоставления начального кода учащимся" выберите раскрывающееся меню **Выбрать репозиторий** .
       - Чтобы выбрать репозиторий шаблонов, начните вводить имя репозитория в текстовом поле, а затем щелкните репозиторий в результатах поиска.
       - Чтобы удалить репозиторий шаблонов, удалите любой текст в текстовом поле.

    {% note %}

    **Примечание:** По умолчанию задание создает пустой репозиторий для каждого учащегося в списке для аудитории.

    {% endnote %}

    ![Снимок экрана: редактор назначений с акцентом на раскрывающемся списке "Выбор репозитория"](/assets/images/help/classroom/edit-assignment-template-repository.png)

1. Чтобы добавить новый тест автоматической оценки, в разделе "Добавить тесты автоматической оценки" выберите раскрывающееся меню **Добавить тест** , а затем выберите метод оценки из отображаемых параметров. Дополнительные сведения см. в статье "[Использование автоматической проверки](/education/manage-coursework-with-github-classroom/use-autograding).
    
    ![Снимок экрана: редактор заданий с акцентом на раскрывающемся списке "Добавить тест"](/assets/images/help/classroom/edit-assignment-add-test.png)

    Кроме того, вы можете изменить или удалить существующие тесты автоматической оценки с помощью {% octicon "pencil" aria-label="The pencil icon" %} или {% octicon "trash" aria-label="The trash icon" %}.

    ![Снимок экрана: редактор заданий с акцентом на значках "Изменить тест" и "Удалить тест"](/assets/images/help/classroom/edit-assignment-edit-test.png)

1.  Чтобы включить или отключить запросы на вытягивание отзывов, выберите или снимите флажок **Включить запросы на вытягивание обратной связи**.

    {% note %}
    
    **Примечание:** Включение или отключение запросов на вытягивание отзывов для назначения не приведет к созданию или удалению запросов на вытягивание отзывов для существующих репозиториев назначений.
    
    {% endnote %}

    ![Снимок экрана: редактор назначений с акцентом на флажок "Включить запросы на вытягивание отзывов"](/assets/images/help/classroom/edit-assignment-feedback.png)

{% data reusables.classroom.update-assignment %}

## Дополнительные материалы

- [Создание отдельного назначения](/education/manage-coursework-with-github-classroom/teach-with-github-classroom/create-an-individual-assignment)
- [Создание назначения группы](/education/manage-coursework-with-github-classroom/teach-with-github-classroom/create-a-group-assignment)
