# AllueXD.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-CuOF+2SnTUfTwSZjCXf01h7uYhfOBuxIhGKPbfEJ3+FqH/s6cIFN9bGr1HmAg4fQ" crossorigin="anonymous">
    <link rel="stylesheet" href="../css/style.css">
    <style>
      body{       
        background-image: url("../source/Fon.png");
        color: black;
      }
      .blocks{
       
        color:    #FFC0CB;  
      }
    </style>
    <title>Нереляционные базы данных</title>
</head>
<body>
  <!--Navigation-->
  <div class="container-xxl">      
    <ul class="nav justify-content-center navbar-dark bg-dark ">
        <li class="nav-item">
        <a class="nav-link active" aria-current="page" href="main.html"><font color = #FFC0CB onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)">NoSQL</font></a>
        </li>
        <li class="nav-item">
        <a class="nav-link" href="keyValue.html"><font color = #FFC0CB onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)"> БД-Ключ-Значение</font></a>
        </li>
        <li class="nav-item">
        <a class="nav-link" href="document.html"><font color = #FFC0CB onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)">БД-Документы</font></a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="graphs.html"><font color = #FFC0CB onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)" >БД-Графы</font></a>
            </li>
        <li class="nav-item">
            <a class="nav-link" href="inMemory.html"><font color = #FFC0CB onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)" >БД в памяти</font></a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="searching.html"><font color = #FFC0CB onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)" >Поисковые БД</font></a>
        </li>
    </ul>
</div>
    <!--main-->
        <div class="container-xxl">      
            
          <div class="border border-bottom-0 border-dark border-5">
            <img src="../source/stripe.png" class="w-100" alt="top-stripe"> 
            <!---->
            <div class="row g-0 bg-light position-relative bg-dark  ">
                <!-- 1st picture-->
              <div class="col-md-3 mb-md-0 p-md-4 bg-dark">
                <svg  viewBox="0 0 16 16" class="bi bi-folder w-100" fill="pink" xmlns="http://www.w3.org/2000/svg">
                  <path d="M9.828 4a3 3 0 0 1-2.12-.879l-.83-.828A1 1 0 0 0 6.173 2H2.5a1 1 0 0 0-1 .981L1.546 4h-1L.5 3a2 2 0 0 1 2-2h3.672a2 2 0 0 1 1.414.586l.828.828A2 2 0 0 0 9.828 3v1z"/>
                  <path fill-rule="evenodd" d="M13.81 4H2.19a1 1 0 0 0-.996 1.09l.637 7a1 1 0 0 0 .995.91h10.348a1 1 0 0 0 .995-.91l.637-7A1 1 0 0 0 13.81 4zM2.19 3A2 2 0 0 0 .198 5.181l.637 7A2 2 0 0 0 2.826 14h10.348a2 2 0 0 0 1.991-1.819l.637-7A2 2 0 0 0 13.81 3H2.19z"/>
                </svg>             
              </div>
              <!-- Paragraph 1-->
              <div class="col-md-8 p-4 pl-md-0 blocks bg-dark blocks border border-5 border-dark")>                
                <h5 onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)" class="mt-0 col-6">Что такое нереляционные базы данных?</h5>
                <p onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)">Нереляционные базы данных создаются для определенных задач, для которых не оптимально использование реляционных субд. NoSQL(not only SQL) обладают гибкими схемами и позволяют разрабатывать современные приложения. Нереляционные базы данных получили широкое распространение благодаря простой разработке, функциональности и лучшей производительностью при любых масштабах.</p>
              
            </div>

              <!-- Paragraph 2-->
              <div class="col-md-11  mb-md-0  p-4 pl-md-0 blocks bg-dark blocks  border  border-5 border-dark ml-1 mr-1">
                <h5 onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)" class="mt-0 col-4">Как работает база данных NoSQL?</h5>
                <p onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)">Нереляционные базы данных используют разнообразные модели данных для доступа и управления данными.
                    Они оптимизированы для приложений, которые работают с большими обьемами данных и нуждаются в низкой задержке и гибких моделях данных.
                    Все это достигается путем смягчения жестких требований к непротиворечивости данных, характерных для других типов БД.</p>
                    <ul>
                      <li onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)"> <div class="col-2"><div class="shrift-color">Реляционные СУБД.</div></div>                        
                         Записи часто разделяются на несколько частей и хранятся в отдельных таблицах, отношения между
                        которыми определяются ограничениями первичных и внешних ключей. Например, в таблице "Книги" имеются столбцы
                        "ISBN"(International serial book number), "Название книги" и "Номер издания", в таблице "Авторы" содержатся столбцы
                        "ID автора" и "Имя автора", а в таблице "Автор-ISBN" - столбцы "Автор" и "ISBN". Реляционная модель создана таким
                        образом, чтобы обеспечить целостность ссылочных данных между таблицами в базе данных. Данные нормализованы для
                        снижения избыточности и в целом оптимизированы для хранения.</li>
                        <br>
                        <li onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)"> <div class="col-2"><div class="shrift-color">Нереляционные СУБД.</div></div>
                          Запись о книге обычно хранится как документ формата JSON. Для каждого элемента(книги)все значения, такие как "Название", "ISBN" и прочее, будут храниться
                          в качестве атрибутов в едином документе. В такой модели данные оптимизированы для интуитивно понятной разработки и 
                          горизонтальной маштабируемости.</li>
                          <br> <br>
                    </ul>
              </div>              
              <div class="col-md-4 mb-md-0 p-md-4 bg-dark">
                <svg  viewBox="0 0 16 16" class="bi bi-union w-100" fill="pink" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" d="M0 2a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v2h2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-2H2a2 2 0 0 1-2-2V2z"/>
                </svg>
              </div>
              <div class="col-md-7 p-4 pl-md-0 blocks bg-dark blocks">
                <h5 onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)" class="mt-0 col-8">Для чего используют нереляционные СУБД?</h5>
                <p onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)">Нереляционные СУБД хорошо подходят для приложений, где требуются гибкие масштабируемые базы данных с высокой производительностью
                  и широким функционалом, чтобы извлекать максимальное удобство пользования. Например, игры и интернет-приложения, мобильные
                  приложения и социальные сети.</p>
                  <ul>
                    <li onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)"> <span class="shrift-color">Гибкость.</span> <br>Как правило, базы данных NoSQL предлагают гибкие схемы, что позволяет осуществлять разработку быстрее и обеспечивает возможность поэтапной реализации. Благодаря использованию гибких моделей данных БД NoSQL хорошо подходят для частично структурированных и неструктурированных данных.</li>
                    <li onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)"><span class="shrift-color">Масштабируемость.</span><br>Базы данных NoSQL рассчитаны на масштабирование с использованием распределенных кластеров аппаратного обеспечения, а не путем добавления дорогих надежных серверов. Некоторые поставщики облачных услуг проводят эти операции в фоновом режиме, обеспечивая полностью управляемый сервис.</li>
                    <li onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)"><span class="shrift-color">Высокая производительность.</span><br>Базы данных NoSQL оптимизированы для конкретных моделей данных и шаблонов доступа, что позволяет достичь более высокой производительности по сравнению с реляционными базами данных.</li>
                    <li onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)"><span class="shrift-color">Широкие функциональные возможности.</span><br>Базы данных NoSQL предоставляют API и типы данных с широкой функциональностью, которые специально разработаны для соответствующих моделей данных.</li>
                  </ul>
              </div>
              <div class="col-md-10  mb-md-0  p-4 pl-md-0 blocks bg-dark blocks  border  border-5 border-dark ml-1 mr-1">
                <h5 onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)" class="mt-0 col-8">Сравнение баз данных SQL (реляционных) и NoSQL (нереляционных)</h5>
                <p onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)">В течение десятилетий центральное место в разработке приложений занимала реляционная модель данных, которая использовалась в реляционных базах данных, таких как Oracle, DB2, SQL Server, MySQL и PostgreSQL. Но в середине – конце 2000‑х годов заметное распространение стали получать и другие модели данных. Для обозначения появившихся классов БД и моделей данных был введен термин «NoSQL». Часто «NoSQL» используется в качестве синонима к термину «нереляционный».</p>
                <p onMouseOver="setIfFocused(this)" onMouseOut="setIfUnfocused(this)">Существует множество типов БД NoSQL с различными особенностями, но в таблице ниже приведены основные отличия баз данных NoSQL от SQL.</p>
              </div>
                
                <!--  Table -->
                <table class="table table-bordered shrift-color">
                  <thead>
                    <tr>
                      <th scope="col"></th>
                      <th scope="col">Реляционные</th>
                      <th scope="col">Нереляционные</th>                      
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">Подходящие рабочие нагрузки</th>
                      <td onMouseOver="setTableFocus(this)" onMouseOut="setTableUnfocus(this)">Реляционные БД предназначены для транзакционных и строго непротиворечивых приложений обработки транзакций в режиме реального времени (OLTP) и хорошо подходят для аналитической обработки в режиме реального времени (OLAP).</td>
                      <td onMouseOver="setTableFocus(this)" onMouseOut="setTableUnfocus(this)">Базы данных NoSQL предназначены для работы с целым рядом шаблонов доступа к данным, в том числе приложений с низкой задержкой. Поисковые БД NoSQL предназначены для аналитики частично структурированных данных. </td>                     
                    </tr>
                    <tr>
                      <th scope="row">Модель данных</th>
                      <td>	
                        Реляционная модель нормализует данные и преобразует их в таблицы, состоящие из строк и столбцов. Схема жестко задает таблицы, строки, столбцы, индексы, отношения между таблицами и прочие элементы базы данных. Такая БД обеспечивает целостность ссылочных данных в отношениях между таблицами. </td>
                      <td>Базы данных NoSQL предоставляют разнообразные модели данных, такие как пары «ключ-значение», документы и графы, оптимизированные для высокой производительности и масштабируемости. </td>                      
                    </tr>
                    <tr>
                      <th scope="row">Свойства ACID</th>
                      <td>Реляционные базы данных обеспечивают набор свойств ACID: атомарность, непротиворечивость, изолированность, надежность.
                        <dl>
                          <li>Атомарность требует, чтобы транзакция выполнялась полностью или не выполнялась вообще.</li>
                          <li>Непротиворечивость означает, что сразу по завершении транзакции данные должны соответствовать схеме базы данных.</li>
                          <li>Изолированность требует, чтобы параллельные транзакции выполнялись отдельно друг от друга.</li>
                          <li>Надежность подразумевает способность восстанавливаться до последнего сохраненного состояния после непредвиденного сбоя в системе или перебоя в подаче питания.</li>
                        </dl>
                      </td>
                      <td>Базы данных NoSQL зачастую предлагают компромисс, смягчая жесткие требования свойств ACID ради более гибкой модели данных, которая допускает горизонтальное масштабирование. Благодаря этому БД NoSQL – отличный выбор для примеров использования с высокой пропускной способностью и низкой задержкой, в которых требуется горизонтальное масштабирование, не ограниченное рамками одного инстанса.</td>                      
                    </tr>
                    <tr>
                      <th scope="row">Производительность</th>
                      <td>Производительность главным образом зависит от дисковой подсистемы. Для обеспечения максимальной производительности часто требуется оптимизация запросов, индексов и структуры таблицы.</td>
                      <td>Производительность обычно зависит от размера кластера базового аппаратного обеспечения, задержки сети и вызывающего приложения.</td>                      
                    </tr>
                    <tr>
                      <th scope="row">Масштабирование</th>
                      <td>Реляционные базы данных обычно масштабируются путем увеличения вычислительных возможностей аппаратного обеспечения или добавления отдельных копий для рабочих нагрузок чтения.</td>
                      <td>Базы данных NoSQL обычно поддерживают высокую разделяемость благодаря шаблонам доступа с возможностью масштабирования на основе распределенной архитектуры. Это повышает пропускную способность и обеспечивает устойчивую производительность почти в неограниченных масштабах.</td>                      
                    </tr>
                    <tr>
                      <th scope="row">API</th>
                      <td>Запросы на запись и извлечение данных составляются на языке SQL. Эти запросы анализирует и выполняет реляционная база данных.</td>
                      <td>Объектно‑ориентированные API позволяют разработчикам приложений без труда осуществлять запись и извлечение структур данных. Благодаря использованию ключей секций приложения могут вести поиск по парам «ключ‑значение», наборам столбцов или частично структурированным документам, содержащим серийные объекты и атрибуты приложений.</td>
                    </tr>
                  </tbody>
                </table>
            </div>          
        </div>
      </div>
    <script src="../js/main.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-popRpmFF9JQgExhfw5tZT4I9/CI5e2QcuUZPOVXb1m7qUmeR2b50u+YFEYe1wgzy" crossorigin="anonymous"></script>
</body>
</html>
