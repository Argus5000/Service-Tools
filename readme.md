<table>
  <tr>
    <td vertical-align="middle"> <img src="./servicetools.svg" alt="Service Tools" width="48px" height="48px"> </td>
    <td vertical-align="middle"> <h1 align="left">Service Tools</h1> </td>
  </tr>
</table>

<h2> ПО для автоматизации и делегирования рутинных административных задач</h2><br>

В процессе работы системных администраторов существует широкий спектр рутинных операций, которые не требуют высокой квалификации исполнителя, однако могут отнимать большой объем времени, приводя к непроизводительным потерям рабочего времени квалифицированных специалистов. Такие операции, как правило, могут оперативно выполняться исполнителями на местах (специалистами, отвечающими за непосредственную поддержку рабочих мест, либо специалистами центров поддержки пользователей, контакт-центров и т.п.), без необходимости обращения к администраторам.<br>
Service Tools разработан чтобы разгрузить администраторов, и позволяет посредством простого и понятного веб-интерфейса делегировать полномочия на выполнение рутинных административных операций специалистам предыдущих линий тех. поддержки (либо сотрудникам смежных подразделений).<br>
Веб-приложение разработано с использованием языка C# и платформы ASP.NET (4.8), а также модулей на языке Powershell, позволяет предоставить пользователю каскадное меню со списком доступных ему модулей, а также ссылок на другие веб-ресурсы. При выборе в меню какого-либо модуля, пользователь может в интерфейсе этого модуля ввести/выбрать необходимые данные, и выполнить требуемые операции (в зависимости от функционала модуля). При этом права доступа пользователей к тем или иным модулям, и отдельному функционалу внутри модулей можно строго разграничить, а выполняемые пользователями действия логируются.<br><br>
Внедрение ПО позволит значительно сократить нагрузку на системных администраторов и делегировать большое количество рутинных операций сотрудникам тех.поддержки, например:
	- предоставление специалистам тех.поддержки необходимого им для работы широкого спектра информации об учетных записях пользователей AD
	- создание, блокировка и разблокировка различных учетных записей
	- создание групп безопасности в AD, изменение их состава
- изменение и сброс паролей учетных записей
	- создание персональных либо сервисных почтовых ящиков, предоставление доступа к ним (доступ к ящику целиком, к отдельным элементам, либо права на отправку сообщений от имени выбранного адресата)
	- создание файловых ресурсов, предоставление/отзыв прав доступа к ним и другие, связанные с ними сервисные операции (изменение ответственного, описания, завершение сессий для освобождения заблокированных файлов и т.п.)
	- поиск и принудительное завершение всех терминальных сессий указанного пользователя (на всех серверах предприятия)

