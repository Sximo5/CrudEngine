# CrudEngine Laravel
CrudEngine is a library that makes you  easier to build and maintenance web application . simple lines of code and you can create a full stable CRUD with nice views. A completely automatic system that even a newbie in PHP can work with! 


### Full CRUD in a few line code
Initial Class on your Controller
```
function index(  Request $request  )
{
	$CrudEngine = new Sclass();
	$this->data['table'] =  $CrudEngine->table('employees')->render();
	return view('table',$this->data);
}
```


### Requirement & Installation
To make work `CrudEngine` work with laravel , you need to make sure its meet with minimum requirment

#### Server & scripts
* Laravel framework version 5.2 or higher

#### Installation

* Extract `CrudEngine` zip and copy all folder and files into your current laravel
* `dump-autoload` via composer

That's it . your `CrudEngine` is ready to use 

View [More example](https://crudengine.sximo5.net/)  or read [documentation](https://github.com/Sximo5/Crud-Engine-Laravel/wiki) 


***


### Features 

* Full CRUD Ajax
* Full CRUD DataTable
* Custom Template Option
* Supported forms | text , textarea , select , checkbox , radio , upload and more


 

