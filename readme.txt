Git is a distributed version control system
Git is free software

function array(arr){
    var newArr = [];
    for(var i = 0 ; i<arr.length-1 ; i++){
	for(var j = 0 ; j<arr.length-1-i ; j++){
		if(arr[j]>arr[j+1]){
		var temp = arr[j]
		arr[j] = arr[j+1]
		arr[j+1] = temp 
}
		
}
}
}