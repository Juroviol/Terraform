# Terraform

## Introdução

As ferramentas de infraestrutura como código (IaC) permitem que você gerencie a infraestrutura com arquivos de configuração ao invés de uma interface gráfica do usuário.

Utilizar Terraform tem várias vantagens sobre o gerenciamento manual de sua infraestrutura:

- Terraform pode gerenciar infraestrutura em múltiplas plataformas de nuvem.
- A linguagem de configuração legível por humanos ajuda a escrever código de infraestrutura rapidamente.
- O estado do Terraform permite que você rastreie as mudanças de recursos em todas as suas implantações.
- Você pode compartilhar as configurações mediante um repositório de controle de versão para que outros possam colaborar na infraestrutura de uma maneira segura.

### Gerencie qualquer infraestrutura

Os plugins do Terraformchamados "providers" permitem ao Terraform interagir com as plataformas de nuvems e outros serviços através de suas APIs.

HashiCorp e a comunidade Terraform já implementaram mais de 1000 provedores para gerenciar recursos na Amazon Web Services (AWS), Azure, Google Cloud Platform (GCP), Kubernetes, Helm, GitHub, Splunk, e DataDog, e etc.

### Rastreie sua infraestrutura

Terraform mantém um rastreamento da sua infraestrutura em um arquivo de estado, o qual atua como uma fonte da verdade para o seu ambiente. Terraform utiliza o arquivo de estado para determinar mudanças na sua infraestrutura para sempre estar de acordo com sua configuração.

## Install Terraform

Para utilizar o Terraform será preciso instala-lo. HashiCorp distribui o Terraform como um pacote binário. Você também pode intalar o Terraform utilizando os gerenciados de pacote populares.

### Instalaçao manual

Iremos abordar a forma de instalar o Terraform de forma manual através de um binário pré-compilado.

Para instalar o Terraform, realize o [download](https://www.terraform.io/downloads.html) do pacote como um arquivo zip correspondente ao seu sistema operacional.

Após o download, extraia o pacote. O Terraform é executado a partir de um arquivo binário chamado terraform. Os demias arquivos do pacot podem ser removidos sem preocupação e o Terraform continuará funcionando.

Finalmente, configure o binário do terraform como variável de ambiente. Este processo será de acordo com seu sistema operacional.
