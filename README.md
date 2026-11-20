# TransCargaMozambique
A empresa “TransCarga Moçambique” está em fase de crescimento no serviço de transporte e distribuição de mercadorias e pretende expandir o funcionamento da sua frota. Porém, os responsáveis pela empresa sempre operaram utilizando planilhas do Excel e ferramentas bastante simples. Sendo assim, nenhum sistema personalizado foi criado e você pretende automatizar o trabalho de gestão da empresa.
Na entrevista com os responsáveis pela empresa, você começou a questioná-los sobre o funcionamento do negócio. Alguns detalhes foram surgindo durante a conversa:
A empresa funciona como uma plataforma de transporte de mercadorias, na qual diferentes transportadores disponibilizam os seus veículos para realizar serviços de transporte e entrega aos clientes.
Cada veículo está associado a um único proprietário, que é responsável pelo veículo. Um proprietário pode possuir um ou mais veículos.
A empresa possui 2 principais tipos de veículos: camiões e carrinhas de carga. Os camiões são utilizados principalmente para transportar grandes quantidades de mercadorias, enquanto as carrinhas são utilizadas para entregas de menor dimensão, principalmente em percursos urbanos.
O responsável pela empresa descreveu o funcionamento da seguinte forma:
“Queremos cadastrar os nossos proprietários/transportadores. Para cada proprietário, precisamos guardar o nome, contacto e documento de identificação. Um proprietário pode ter vários veículos, mas cada veículo pertence apenas a um proprietário. Também precisamos controlar os veículos. Para os camiões, queremos registar a matrícula, marca, modelo e capacidade de carga em toneladas. Para as carrinhas, queremos controlar os mesmos dados. Os clientes solicitam serviços de transporte. Para cada cliente, queremos guardar o nome, contacto e localização. Quando um cliente solicita um serviço, devemos registar o carregamento da mercadoria. O carregamento deve indicar o cliente, o veículo utilizado, a quantidade de mercadoria, o local de origem, o destino, a data e o valor cobrado pelo serviço. Precisamos também garantir que a quantidade de mercadoria transportada não ultrapasse a capacidade máxima do veículo.”
Por exemplo, se uma carrinha possui capacidade máxima de 2 toneladas, não poderá ser registado um carregamento de 3 toneladas para esse veículo.
1. É solicitado a cada grupo o desenvolvimento de um pequeno software informático da empresa “TransCarga Moçambique”, com o seguinte menu funcional (o uso de interfaces gráficas é opcional):
    a. Cadastrar e registar num ficheiro de objectos os proprietários/transportadores, contendo pelo menos: Nome; Contacto; Documento de identificação.
    b. Cadastrar e registar num ficheiro de objectos os veículos da frota, podendo ser: Camiões; e Carrinhas de carga.
    c. Cada veículo deve estar associado a um proprietário.
    d. Actualizar os dados dos proprietários e dos veículos.
    e. Listar apenas os camiões, pela ordem crescente da capacidade de carga.
    f. Listar apenas as carrinhas de carga, pela ordem crescente da capacidade de carga.
    g. Cadastrar e registar os clientes, contendo pelo menos: Nome; Contacto; Localização.
    h. Registar carregamentos/transportes, contendo: Cliente; Veículo utilizado; Proprietário do veículo; Quantidade de mercadoria; Local de origem; Destino; Data; Valor cobrado.
    i. Validar o carregamento, garantindo que a quantidade de mercadoria não ultrapassa a capacidade máxima do veículo.
    j. Listar os carregamentos/transportes realizados, apresentando as principais informações do serviço.
    k. Listar os transportes realizados por um determinado proprietário, permitindo verificar os serviços realizados pelos veículos desse proprietário.
    l. Consultar o total arrecadado pelos serviços de um determinado veículo.
