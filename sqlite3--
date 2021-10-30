const sqlite3 = require("sqlite3").verbose();

let db = new sqlite3.Database("D:/KIP_DB/users.db");
let sql = "SELECT DISTINCT * FROM '140289593'";

db.all(sql, [], (err, rows) => {
  if (err) {
    throw err;
  }
  rows.forEach((row) => {
    console.log(row.name);
  });
});
db.close();
