var doublevalResult = [10,8,12,36].map(function(value,doubleValue){ 
        return doubleValue = value * 2; 
});
var filtervalResult = doublevalResult.filter(function(value,filterValues){ 
    if(value > 20){ 
        return filterValues=value; 
    }
});
var filtersumResult = filtervalResult.reduce(function(sum,value){ 
        return sum+=value; 
});