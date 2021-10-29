# secure-php-coding

best way to secure coding while making php web project

1) use .htaccess to restrict user to watch list of file in **directory**  or create blank index.php in every directory <br>
<p><b> while making login page</p>
  <ul>
    <li> add html validation at form such as required , email , max size, min size, etc </li>
   <li> add validation at serverside  show that if hacker try to send ilegal input inside db from url it can be santize  </li>
    <li> add <b>CSRF</b> token to mitegate cross site reuest forgery  </li>
    <li> use <b> PDO with Prepared Statements </b> to limit sql injection  </li>
 
