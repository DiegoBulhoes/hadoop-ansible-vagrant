# Hadoop

Para iniciar o lab será necessario criar as _keys_ dentro do diretorio key:

```shell
 ssh-keygen -q -t rsa -f id_rsa
```

Para iniciar o lab basta execultar o seguinte comando:

```shell
vagrant up
```

A maquina que será criada possui o usuario **hadoop** no qual a senha é **password**. Essa VM esta configura para inicializar os seguintes serviços:

```text
ResourceManager
NodeManager
Jps
DataNode
SecondayNodeManager
NameNode
```
