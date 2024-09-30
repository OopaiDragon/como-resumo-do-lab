# Resumo do Lab de Computação em Nuvem

## Introdução
Neste laboratório da DIO sobre **computação em nuvem**, explorei diversos conceitos importantes que fundamentam a infraestrutura moderna de TI. A nuvem oferece benefícios como escalabilidade, elasticidade, alta disponibilidade e segurança, permitindo que empresas e desenvolvedores se concentrem no crescimento e inovação, ao invés de gerenciar infraestrutura física. Este resumo abrange as principais lições aprendidas sobre os tipos de serviço em nuvem (IaaS, PaaS, SaaS) e o modelo de responsabilidade compartilhada.

## Tipos de Serviço em Nuvem

### 1. IaaS (Infraestrutura como Serviço)
O **IaaS** oferece o nível mais básico de serviços na nuvem, onde o provedor disponibiliza infraestrutura física e virtual sob demanda, como servidores, máquinas virtuais, redes e sistemas operacionais. Com IaaS, você paga conforme o uso dos recursos e tem a flexibilidade de gerenciar suas próprias aplicações e sistemas operacionais, sem se preocupar com hardware físico.

**Principais características**:
- Controle total sobre a infraestrutura.
- Uso sob demanda (pagamento conforme o uso).
- Mais flexível para configurar e gerenciar.
- Exige que o cliente cuide de atualizações e manutenção do sistema operacional.

### 2. PaaS (Plataforma como Serviço)
O **PaaS** fornece uma plataforma completa para desenvolvimento, teste e implantação de aplicativos, sem que os desenvolvedores precisem gerenciar a infraestrutura subjacente. A plataforma oferece ferramentas para desenvolvimento, bancos de dados, middleware, e outros componentes necessários para construir aplicações rapidamente.

**Principais características**:
- O provedor gerencia a infraestrutura e a plataforma.
- Ideal para desenvolvimento ágil de aplicativos.
- O cliente se concentra no desenvolvimento de código e lógica de negócios.
- A escalabilidade e atualizações são gerenciadas pelo provedor.

### 3. SaaS (Software como Serviço)
O **SaaS** permite que os usuários acessem aplicativos prontos pela internet. O provedor de SaaS cuida de toda a infraestrutura, manutenção, e atualização do software. O usuário apenas se conecta ao serviço via navegador ou aplicativo.

**Principais características**:
- Nenhuma gestão de infraestrutura por parte do cliente.
- Pagamento por assinatura ou uso.
- Alta disponibilidade e acessibilidade, geralmente acessível por qualquer dispositivo com conexão à internet.

## Implementação de Máquina Virtual (VM) na Nuvem
Durante o laboratório, aprendi sobre a **criação de uma máquina virtual** no portal da nuvem, onde foi necessário definir várias configurações como:
- Escolha do sistema operacional (ex: Windows ou Linux).
- Tamanho da VM (quantidade de CPUs e RAM).
- Configurações de rede (definindo se a VM será pública ou privada).
- Armazenamento adicional (discos SSD ou HDD).
- Configuração de conexões (RDP ou SSH).

Essas opções permitem criar uma infraestrutura personalizada, onde você é responsável por gerenciar a VM, instalar o software e configurar as atualizações, um exemplo clássico do modelo **IaaS**.

## Criação de Banco de Dados SQL na Nuvem
Outro recurso explorado foi a **criação de um banco de dados SQL** na nuvem. No laboratório, configuramos um banco de dados SQL com os seguintes passos:
- Definição do nome do banco e escolha de um servidor.
- Configuração de autenticação (ex: autenticação SQL ou integração com o Microsoft Azure AD).
- Seleção do nível de redundância de dados (LRS ou GRS).
- Estimativa de custos com base nas opções escolhidas.

Essas configurações são importantes para garantir a disponibilidade, escalabilidade e segurança dos dados armazenados na nuvem. O gerenciamento do banco de dados também é feito no modelo **PaaS**, onde o provedor cuida da plataforma e o cliente gerencia apenas os dados e as aplicações.

## Modelo de Responsabilidade Compartilhada
Na computação em nuvem, existe um conceito chamado **responsabilidade compartilhada**, onde tanto o provedor quanto o cliente são responsáveis pela segurança e gestão dos serviços. A responsabilidade exata depende do tipo de serviço (IaaS, PaaS, SaaS):
- **IaaS**: O cliente é responsável pela segurança das aplicações, sistemas operacionais, e dados, enquanto o provedor cuida da infraestrutura.
- **PaaS**: O cliente gerencia apenas os dados e as aplicações, enquanto o provedor cuida da plataforma e da infraestrutura.
- **SaaS**: O provedor cuida de tudo, e o cliente apenas utiliza o software.

## Conclusão
Durante este laboratório, aprendi como os diferentes tipos de serviço em nuvem (IaaS, PaaS e SaaS) oferecem níveis variados de controle e responsabilidade. Esses serviços são fundamentais para modernizar a infraestrutura de TI, tornando-a mais ágil, escalável e fácil de gerenciar. O modelo de responsabilidade compartilhada também é um fator importante ao considerar a adoção da nuvem, pois define claramente quais partes são gerenciadas pelo provedor e pelo cliente.

