Projeto do ifood 
Integrantes do grupo : Joao Manoel Pereira Bem Bom , Marcello Venzel Zaninotto 

Este projeto é uma demonstração robusta de um sistema de gerenciamento de pedidos e restaurantes,
desenvolvido integralmente em Java e utilizando a biblioteca JavaFX para a construção da interface gráfica.
O principal objetivo é fornecer uma plataforma com fluxos de trabalho distintos para dois tipos de
usuários: Dono do Restaurante (Administrador) e Cliente (Usuário Final).

O design do sistema prioriza os princípios da Programação Orientada a Objetos (POO), utilizando
intensivamente Herança, Polimorfismo e modelagem de relações complexas (Agregação e Composição) 
para garantir um código limpo, modular e escalável.

O desenvolvimento deste sistema visa atingir os seguintes objetivos principais:

  - Segregação de Responsabilidades: Criar um ambiente isolado para o gerenciamento (Dono) e para a experiência do usuário (Cliente).
  - Modelagem Realista de Produtos: Implementar herança para modelar produtos especializados (Comida e Bebida) que possuem atributos
    e comportamentos únicos, demonstrando o poder do polimorfismo em cálculos de preço e tempo.
  - Experiência de Usuário Interativa: Utilizar o poder do JavaFX (com .fxml gerenciados pelo Scene Builder)
    para criar interfaces intuitivas e reativas.
  - Demonstração de POO: Servir como um exemplo prático e didático de como aplicar conceitos avançados de POO em um projeto real.

O sistema é dividido em duas áreas com funcionalidades distintas:

 - Dono do Restaurante (Administrador): Responsável pelo Cadastro do Restaurante e pelo Gerenciamento de Produtos (adicionar, modificar, remover).
   O dono cadastra produtos especializados, como Comida (com tipo de cozinha e atributos vegano/vegetariano) e Bebida (com tamanho e indicador alcoólico).
 - Cliente (Usuário Final): Pode Visualizar Restaurantes, Selecionar Produtos para montar um pedido e o sistema calcula automaticamente
   o Preço Total e o Tempo de Espera.
   
O fluxo inicia com um Login/Cadastro e direciona o usuário para sua área específica:

 - Dono: Gerencia o cardápio e salva as alterações.
 - Cliente: Navega pelos restaurantes, monta o pedido, visualiza o total/tempo de espera e finaliza a compra.
