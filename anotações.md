## Classes de teste e métodos de teste
De modo semelhante às convenções para arquivos e funções, 
as classes de teste e os métodos de teste usam as seguintes convenções:

- As classes de teste têm o prefixo "Test"
- Os métodos de teste têm o prefixo "test_"

### Uma das principais diferenças em relação à biblioteca unittest do Python é que não existe a necessidade de herança.

## Métodos e classes de teste
Além de escrever funções de teste, o Pytest permite que você use classes. Como já mencionamos, não há necessidade de herança 
e as classes de teste seguem algumas regras simples. O uso de classes oferece mais flexibilidade e reutilização. Como você verá
a seguir, o Pytest não atrapalha e evita obrigar você a escrever testes de uma maneira específica.

## Métodos Auxiliares

### Em uma classe de teste, você pode usar alguns métodos para configurar e desinstalar a execução do teste. O Pytest os executará automaticamente se forem definidos. Para usar esses métodos, você precisa saber que eles têm uma ordem e um comportamento específicos.

- setup: é executado uma vez antes de cada teste em uma classe
- teardown: é executado uma vez após cada teste em uma classe
- setup_class: é executado uma vez antes de todos os testes em uma classe
- teardown_class: é executado uma vez após todos os testes em uma classe

