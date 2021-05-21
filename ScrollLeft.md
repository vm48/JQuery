### Определение вертикального скролла
```js
$(".cecj-integers__items").on( 'scroll', function(){
		console.log($(".cecj-integers__items").scrollLeft());
		if ($(".cecj-integers__items").scrollLeft()>10){
			setTimeout(block_anim_css('.cecj-integers__mobile-arrow',{'display': 'none','visibility': 'hidden'}), 500);
		}else {
			setTimeout(block_anim_css('.cecj-integers__mobile-arrow',{'display': 'block','visibility': 'visible'}), 500);
		}
	});
```
