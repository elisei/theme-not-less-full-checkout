# Theme Not Less for Full Checkout

Tema para o Full Checkout para lojas que não usam less.

## Instalação

### Via Composer

``` sh
composer require o2ti/theme-not-less-full-checkout
```

Após a instalação registre o módulo e faça a compilação 
``` sh
bin/magento setup:upgrade
bin/magento setup:di:compile
```
E se seu site estiver em produção faça o deploy de conteúdo
``` sh
bin/magento setup:static:deploy
```

### Manual (upload de arquivos)

Faça o download [Clicando aqui](https://github.com/elisei/theme-not-less-full-checkout/archive/refs/heads/main.zip)

Em seu projeto:
- Acesse a pasta app
- Dentro dessa pasta crie ou acesse caso já tenha, a pasta code
- Dentro da pasta crie ou acesse a pasta O2TI
- Dentro da pasta O2TI crie a pasta ThemeNotLessFullCheckout
- Descompacte o conteúdo do zip recebido dentro dessa pasta

O caminho completo do módulo deverá ser:
app/code/O2TI/ThemeNotLessFullCheckout

<details>
<summary>Veja no vídeo exemplo desse passo a passo</summary>
<p>

https://user-images.githubusercontent.com/1786389/144749573-6264bb6b-6c63-49d1-8ff8-0da536818934.mp4

</p>
</details>

Após a instalação registre o módulo e faça a compilação 
``` sh
bin/magento setup:upgrade
bin/magento setup:di:compile
```
E se seu site estiver em produção faça o deploy de conteúdo
``` sh
bin/magento setup:static:deploy
```

## License

[Open Source License](LICENSE.txt)
