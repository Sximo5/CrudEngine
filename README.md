# SxClass
Sximo Class For Laravel

## Include SxClass Library

Initial Class on your Controller

```
  use App\Library\Sclass;
```
## Initial New Class
```
  function index(  Request $request  ) {
    $sximo = new Sclass();
  }  
```

### Simple Usage
```
	function index(  Request $request  )
	{

		$sximo = new Sclass();
		$this->data['table'] =  $sximo->table('employees')->render();

		return view('table',$this->data);
	}
```  

