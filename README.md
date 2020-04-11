## Try it

[https://my-json-server.typicode.com/typicode/demo](https://my-json-server.typicode.com/typicode/demo)

## Use your own data

Fork it and change `db.json` values or create a repo with a `db.json` file.

EXEMPLE #1 fetch all db :
fetch('https://my-json-server.typicode.com/SamuelPratte/demo/db')
  .then((response) => {
    return response.json();
  })
  .then((data) => {
    console.log(data);
  });


EXEMPLE #2 fetch second student :
fetch('https://my-json-server.typicode.com/SamuelPratte/demo/students/2')
  .then(response => response.json())
  .then(json => console.log(json))
