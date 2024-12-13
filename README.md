# Tipos de Serviços de Nuvem - configurando uma instância de Banco de Dados

## Máquinas Virtuais
Ao criar uma máquina virtual, é possível selecionar uma **imagem de sistema operacional** conforme sua necessidade.  

Entre as configurações disponíveis, está a opção de **tamanho**, que define as características do sistema operacional, como memória, CPU e armazenamento, além do custo mensal associado.  

O processo de configuração inclui diversas abas, como:
- **Monitoramento**  
- **Discos**  
- **Rede**  
- Entre outras.  

Essas abas permitem ajustes detalhados para personalizar a máquina virtual de acordo com os requisitos do usuário.

---

## Banco de Dados
Na configuração de um banco de dados, o usuário deve:
1. **Escolher um nome** para o servidor.
2. **Definir a localização** do servidor.  

Após isso, o servidor é criado, e algumas configurações adicionais precisam ser realizadas, como:  
- **Método de autenticação:**  
  O usuário pode escolher entre as seguintes opções:  
  - Autenticação com **Microsoft Entra**.  
  - Combinação de **Microsoft Entra** e autenticação do **SQL**.  
  - Apenas autenticação do **SQL**.

- **Modelo de redundância:**  
  O usuário escolhe entre:
  - **Backup local**  
  - **Backup de zona**  
  - **Backup geográfico**

Ao final da configuração, um **resumo dos custos** estimados para o serviço de banco de dados será exibido.

---

## IaaS - Infraestrutura como Serviço
O **IaaS (Infrastructure as a Service)** é o modelo de nuvem que exige maior envolvimento do usuário na configuração.  

Os dois serviços mencionados anteriormente (**Máquinas Virtuais** e **Banco de Dados**) pertencem a esta modalidade.  

### Outros modelos de nuvem:
- **PaaS (Platform as a Service):**  
  Oferece uma plataforma gerenciada para desenvolvimento e execução de aplicações.  

- **SaaS (Software as a Service):**  
  Fornece software prontos para uso, acessados diretamente via internet.  

A responsabilidade do cliente em relação à gestão do serviço diminui nesta ordem:  
**IaaS > PaaS > SaaS.**
