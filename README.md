# Geral

Jogo de pedra, papel e tesoura em Java com o framework Spring.


# Demonstração

Há uma gravação mostrando o jogo.


# Atenção

**Fique atento: confira se a porta 8080 está livre antes de subir a aplicação.**


# Versões da linguagem

Com estas versões:

- **8**: **não** funciona;
- **17**: funciona;
- **21**: funciona.


# Trocando a versão da linguagem

No Linux Mint 20 usei o utilitário de alternativas:

```
sudo update-java-alternatives <caminho-da-versão>
```

Exemplo:

```
sudo update-java-alternatives /usr/lib/jvm/java-1.17.0-openjdk-amd64
```

Para listar as versões instaladas e os caminhos correspondentes:

```
sudo update-java-alternatives --list
```


# Executando

```
mvn spring-boot:run
```


# Acessando

No navegador, abra o endereço da máquina local na porta 8080.