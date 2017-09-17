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

View [example](https://crudengine.sximo5.net/)  or read [docs](https://github.com/Sximo5/Crud-Engine-Laravel/wiki) 

 

