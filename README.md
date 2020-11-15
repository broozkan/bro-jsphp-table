# bro-jsphp-table
A vanilla javascript, jquery and vanilla php table framework for large data

Getting all amount of large data can make website slow. With this framework we are getting data partially and display and paginate it without refresh the page.


## Installation
Include table.js, jquery-serialize.js file inside page

## Usage
Fill table attributes

---html
<table class="table table-hover" function="foo-list" id="foo-list" model="foo" is-override="true" page-number="1" item-per-page="25" override-function="overrideFooList">


Trigger to load data (you can trigger it after updating table content)
---javascript
let table = new Table();
let tbl = $("#foo-table");
table.loadCustomTable(tbl);
table = null;


## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
