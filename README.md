# Automacao-Web-Excel
Automação Excel com HTML || CSS || JS

# Inicio

## HTML
~~~html
<!DOCTYPE html>
<html>
  <head>
    <title>Account registration form</title>
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600' rel='stylesheet' type='text/css'>
    <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700" rel="stylesheet">
  </head>
  <body>
    <div class="main-block">
    <form action="/">
      <h1>Automação WEB - EXCEL</h1>
      <fieldset>
        <legend>
          <h3>Detalhes Lugar</h3>
        </legend>
        <div  class="account-details">
          <div><label>Setor</label>              
            <select>
            <option value=""></option>
            <option value="Ariri">Ariri</option>
            <option value="Bengui">Bengui</option>
            <option value="Cordeiro de Farias">Cordeiro de Farias</option>
            <option value="Catalina">Catalina</option>
            <option value="IPASEP/Maguari">IPASEP/Maguari</option>
            <option value="IPASEP/Satélite">IPASEP/Satélite</option>
            <option value="Panorama XXI">Panorama XXI</option>
            <option value="Pratinha">Pratinha</option>
            <option value="Tenoné">Tenoné</option>
            <option value="Cohab">Cohab</option>
            <option value="Paracuí II">Paracuí II</option>
            <option value="São Roque">São Roque</option>
            <option value="Souza Franco">Souza Franco</option>
            <option value="Eduardo Angelim">Eduardo Angelim</option>
            <option value="Tocantins">Tocantins</option>
            <option value="Águas Negras">Águas Negras</option>
            <option value="Pratinha I">Pratinha I</option>
            <option value="Pratinha II">Pratinha II</option>
            <option value="Quinta dos Paricás">Quinta dos Paricás</option>
            <option value="Viver Primavera">Viver Primavera</option>
            <option value="Rdo. Jinkings">Rdo. Jinkings</option>
            <option value="Mata Fome I">Mata Fome I</option>
            <option value="Água Boa">Água Boa</option>
            <option value="Brasília">Brasília</option>
            <option value="São João">São João</option>
            <option value="Benedito Monteiro">Benedito Monteiro</option>
            <option value="Moradia de Deus">Moradia de Deus</option>
            <option value="Cotijuba">Cotijuba</option>
            <option value="Mosqueiro Farol">Mosqueiro Farol</option>
            <option value="Mosqueiro MURUBIRA">Mosqueiro MURUBIRA</option>
            <option value="Mosqueiro BAÍA DO SOL">Mosqueiro BAÍA DO SOL</option>
            <option value="Mosqueiro CARANANDUBA">Mosqueiro CARANANDUBA</option>
            <option value="Mosqueiro P. Manoel Rayol">Mosqueiro P. Manoel Rayol</option>
            <option value="Mosqueiro PRAIA DO BISPO">Mosqueiro PRAIA DO BISPO</option>
          </select></div>
        </div>
      </fieldset>
      <fieldset>
        <legend>
          <h3>Horas trabalhadas</h3>
        </legend>
        <div  class="personal-details">
          <div>
            <div><label>Quantidade de poços:</label>
                <select>
                    <option value=""></option>
                    <option value="pc1">Poço 1</option>
                    <option value="pc2">Poço 2</option>
                    <option value="pc3">Poço 3</option>
                    <option value="pc4">Poço 4</option>
                  </select>
                </div>
                <div class="birthdate">
                    <label>Dia Trabalhado:</label>
                    <div class="bdate-block">
                      <select class="day" required style="width: 50px;">
                        <option value=""></option>
                        <option value="01">01</option>
                        <option value="02">02</option>
                        <option value="03">03</option>
                        <option value="04">04</option>
                        <option value="05">05</option>
                        <option value="06">06</option>
                        <option value="07">07</option>
                        <option value="08">08</option>
                        <option value="09">09</option>
                        <option value="10">10</option>
                        <option value="11">11</option>
                        <option value="12">12</option>
                        <option value="13">13</option>
                        <option value="14">14</option>
                        <option value="15">15</option>
                        <option value="16">16</option>
                        <option value="17">17</option>
                        <option value="18">18</option>
                        <option value="19">19</option>
                        <option value="20">20</option>
                        <option value="21">21</option>
                        <option value="22">22</option>
                        <option value="23">23</option>
                        <option value="24">24</option>
                        <option value="25">25</option>
                        <option value="26">26</option>
                        <option value="27">27</option>
                        <option value="28">28</option>
                        <option value="29">29</option>
                        <option value="30">30</option>
                        <option value="31">31</option>
                      </select>
                      <select class="mounth" required>
                        <option value=""></option>
                        <option value="January">January</option>
                        <option value="February">February</option>
                        <option value="March">March</option>
                        <option value="April">April</option>
                        <option value="May">May</option>
                        <option value="June">June</option>
                        <option value="July">July</option>
                        <option value="August">August</option>
                        <option value="September">September</option>
                        <option value="October">October</option>
                        <option value="November">November</option>
                        <option value="December">December</option>
                      </select>
                      <input type="text" name="name" required>
                    </div>
                  </div>
            <div><label>Horas trabalhadas:</label><input type="number" name="name" min="0" max="24"></div>
            <div><label>Minutos trabalhados:</label><input type="number" name="name" min="0" max="60"></div>
            <div><label>Segundos trabalhados:</label><input type="number" name="name" min="0" max="60"></div>
          </div>
        </div>
      </fieldset>
      <fieldset>
        <legend>
          <h3>Terms and Mailing</h3>
        </legend>
        <div  class="terms-mailing">
          <div class="checkbox">
            <input type="checkbox" name="checkbox"><span>I accept the <a href="http://www.cosanpa.pa.gov.br/">Privacy Policy for Cosanpa.</a></span>
          </div>
      </fieldset>
      <button type="submit" href="/">Submit</button>
      <footer>
        <div class="checkbox">
          <span>Feito na unidade <a href="http://www.cosanpa.pa.gov.br/">UNAM.</a></span>
        </div>
      </footer>
    </form>

    
    </div> 
  </body>
</html>
~~~
## CSS
~~~css
html, body {
      min-height: 100%;
      }
      body, div, form, input, select, p { 
      padding: 0;
      margin: 0;
      outline: none;
      font-family: Roboto, Arial, sans-serif;
      font-size: 14px;
      color: #666;
      }
      h1 {
      margin: 0;
      font-weight: 400;
      text-align: center;
      color: #8ebf42;
      }
      h3 {
      margin: 12px 0;
      color: #8ebf42;
      }
      .main-block {
      display: flex;
      justify-content: center;
      align-items: center;
      background: #fff;
      }
      form {
      width: 100%;
      padding: 20px;
      }
      fieldset {
      border: none;
      border-top: 1px solid #8ebf42;
      }
      .account-details, .personal-details {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      }
      .account-details >div, .personal-details >div >div {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
      }
      .account-details >div, .personal-details >div, input, label {
      width: 100%;
      }
      label {
      padding: 0 5px;
      text-align: right;
      vertical-align: middle;
      }
      input {
      padding: 5px;
      vertical-align: middle;
      }
      .checkbox {
      margin-bottom: 10px;
      }
      select, .children, .gender, .bdate-block {
      width: calc(100% + 26px);
      padding: 5px 0;
      }
      select {
      background: transparent;
      }
      .gender input {
      width: auto;
      } 
      .gender label {
      padding: 0 5px 0 0;
      } 
      .bdate-block {
      display: flex;
      justify-content: space-between;
      }
      .birthdate select.day {
      width: 35px;
      }
      .birthdate select.mounth {
      width: calc(100% - 94px);
      }
      .birthdate input {
      width: 38px;
      vertical-align: unset;
      }
      .checkbox input, .children input {
      width: auto;
      margin: -2px 10px 0 0;
      }
      .checkbox a {
      color: #8ebf42;
      }
      .checkbox a:hover {
      color: #82b534;
      }
      button {
      width: 100%;
      padding: 10px 0;
      margin: 10px auto;
      border-radius: 5px; 
      border: none;
      background: #8ebf42; 
      font-size: 14px;
      font-weight: 600;
      color: #fff;
      }
      button:hover {
      background: #82b534;
      }
      @media (min-width: 568px) {
      .account-details >div, .personal-details >div {
      width: 50%;
      }
      label {
      width: 40%;
      }
      input {
      width: 60%;
      }
      select, .children, .gender, .bdate-block {
      width: calc(60% + 16px);
      }
      }
~~~
