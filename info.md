# css selectors 

next_page = response.css('a[title=Next]::attr(href)').get()
all_products = response.css('div.product-item-info').get()
price = response.css('span.price::text').get()
link = response.css('a.product-item-link::attr(href)').get()
title = response.css('img.product-image-photo.image::attr(alt)').get()
