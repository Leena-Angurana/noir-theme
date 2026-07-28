##Layout
my understading : its like a skeleton which tells about the structure of our website 
theme.liquid is in layout - which loads every page and under its architecture shopify inserts page whether its homepage, product page, collection page or cart page. (Special line of code for that {{content_for_layout}})


##Templates 
my understading : this is a blueprint which tells which page is this if customer opens the product page
it contains every page for our website such as index.json , product.json, collection.json etc. 

##Assets 
my understading : its like a toolbox where we store static information eg. our css, js or logo falls under assets. we can store them in assets and use as our requirement

##Sections 
my understanding : its a reusable blocks of code (section) - eg. our homepage is consist of so many sections such as hero banner, featured products, curated collection, testimonials, FAQs etc. they all are reusable section which we can use across our website(theme) used for maintainbility, scalibility, consistency, and reusability.

##Snippets
my understanding : its very much like sections but comparatively of small code or component such as buttons, icons, price, accordions, etc. which we need to use again and again in our theme, we can simply create a snippet for that and render whenever needed

##Config
my understanding : it tells the merchant what are the settings available and where it gets store. Basically there are two types of files settings.schema.json and settings.data.json. First one tells what the settings available and second one stores the value which merchant has chose. 

##Locales 
my understanding : Locales are languages that our store supports and by creating it we dont need to manually type everything in different languages we can simply use it 
eg Products.product.add-to-cart.



DEBUGGING (1): My changes were not appearing because I added them to `sections/product.liquid`, while the active product template (`product.json`) was rendering `sections/main-product.liquid`.

LEARNING : Before debugging Liquid code, always verify which template and section are actually responsible for rendering the current page.