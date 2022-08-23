# Projeto StarClimate
Baseado em uma estrutura de node-red, o Starclimate visa buscar dados para otimizar sua plantação

## Embasamento Disciplinar
O projeto visa utilizar o conhecimento adquirido em disciplinas como Programação Web II, Novas Tecnologias (IoT) e Bancos de Dados

## Modelagem de banco de dados

```mermaid
classDiagram
      Web_User .. Login
      Web_User.. App_Use
      Web_User: int user_id_PK
      Web_User: int user_pwd
      Web_User: String user_name
      Web_User: String user_email
      class Login{
          int login_datetime
          int user_id_FK
      }
      class App_Use{
          int update_id_PK
          int user_id_FK
          int action_datetime
      }
```
## Diagramas de Casos de Uso

![My Image](usecaseadmin.png)
![My Image](usecasecustomer.png)

## Diagrama de Sequência

![My Image](sequence.png)

## Formatação do sistema

![My Image](flows.png)

## Tela inicial (MVP)

![My Image](initialscreen.png)