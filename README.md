none-prefix
===========

Simple and Comprehensive Less mixin to add vendor prefix auto   

Different with other less library    
This library is more free   

Example:
 
	 .div{
	  -webkit-border-radius: 10px;
	  -moz-border-radius: 10px;
	  -ms-border-radius: 10px;
	  -o-border-radius: 10px;
		border-radius: 10px;
	  }

is equal to

 	.prefix(border-radius,10px);
  
it's cool and amazing   

if you have no idea wether you should add vendor prifixer, just use .prefix() mixin

All in all, it's no hurt!
 
Don't look down it as it is really simple

Because great is usually from simple
