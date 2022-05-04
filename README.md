# Pacote de tradução para PT BR oficial do Magento

## Instalação via composer

- Execute os comandos:

```
composer require alexnovaes/traducao_magento2_pt_br
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy pt_BR -f
php bin/magento cache:flush
```