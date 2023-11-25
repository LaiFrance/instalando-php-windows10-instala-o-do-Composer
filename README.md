# instalando-php-windows10
guia de como instalar o php globalmente no windowns 10 

# Instalação do PHP no Windows 10

Este guia fornece instruções detalhadas sobre como instalar o PHP globalmente no Windows 10 e configurar as variáveis de ambiente.

## Passo 1: Download do PHP
Baixe o Arquivo zip contido nesse repositório

![scrnli_25_11_2023_14-45-42](https://github.com/LaiFrance/instalando-php-windows10/assets/91226847/27ba32bd-5240-448c-a791-852edce1a743)

**ou**
<br>
Baixe a versão mais recente do PHP para Windows no [site oficial do PHP](https://windows.php.net/download/). 

Extraia o arquivo baixado para um diretório de sua escolha. Por exemplo, `C:\PHP`.

## Passo 3: Configuração das Variáveis de Ambiente
1. Clique com o botão direito em "Este PC" e selecione "Propriedades".
2. Clique em "Configurações avançadas do sistema".
3. Clique em "Variáveis de Ambiente".
   <br>
![Propriedades do Sistema 25_11_2023 14_48_45](https://github.com/LaiFrance/instalando-php-windows10/assets/91226847/c1ff920d-fa79-4be1-958c-35e80f256083)


<br>

![Propriedades do Sistema 25_11_2023 14_52_49](https://github.com/LaiFrance/instalando-php-windows10/assets/91226847/0994d9db-4410-41b9-b801-457dad1bb73c)

4. Em "Variáveis do Sistema", clique em "Novo" para adicionar uma nova variável.
   

- **Nome da Variável:** `PHP_HOME`
- **Valor da Variável:** O caminho completo para o diretório onde o PHP foi extraído (por exemplo, `C:\PHP`).
   
![Propriedades do Sistema 25_11_2023 14_54_32](https://github.com/LaiFrance/instalando-php-windows10/assets/91226847/c904ff3f-a6d9-43d1-a44f-3d778d5f8883)

  



## Passo 4: Verificação da Instalação

Abra o Prompt de Comando e digite:

```bash
php -v
