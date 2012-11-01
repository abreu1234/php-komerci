Biblioteca PHP para acesso � plataforma Komerci da Redecard

Por enquanto apenas as seguintes fun��es est�o dispon�veis (vender, cancelar venda, visualizar cupom):
* GetAuthorized
* VoidTransaction
* Cupom

Exemplo de impress�o de cupom:
```php
<?php
include("redecard.php");


print_r(Cupom(array(
	'Data' => '20121031', 
	'NumCV' => '123456789', 
	'NumAutor' => '123456', 
	'Filiacao' => '123456789' 
)));
?>
```