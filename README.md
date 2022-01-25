# webtec-firewall
Sistema de proteção contra Hackers para Sites em PHP e WordPress

Adicione a parte 1 no inicio do código e a parte 2 no final do seu código php. 
Poderá utilizar em seu site wordpress ou site em php puro! 

Parte 1 no inicio do seu código php:

/**
 * <b> WEBTEC FIREWALL 2022 </b>
 * Atualizado dia 25/01/2022 por Maykon Silveira
 * Criado dia 18/01/2018 por Maykon Silveira - maykonsilveira.com.br
 * 2022, Maykon Silveira - WEBTEC TECHNOLOGIES
 * Site oficial www.maykonsilveira.com.br Cursos online.
 * CRIADO DIA 18/01/2018 POR MAYKON SILVEIRA maykonsilveira.com.br
 * Versão 2.1
 */

//PARTE 1 - INICIO DO WEBTEC FIREWALL CRIADO DIA 14/03/2020 POR MAYKON SILVEIRA maykonsilveira.com.br
                //1ª OPÇÃO CASO 
               // $maykonIp = filter_input(INPUT_SERVER, 'REMOTE_ADDR'); 
                // 2ª OPÇÃO
                $maykonIp = $_SERVER['REMOTE_ADDR']; 
                $maykonEmail = "cursos@maykonsilveira.com.br";
                $maykonMsg = "Você não tem permissão para acessar esta página!";

                $ip = $maykonIp;
                $ip    = substr($ip,0,3);
                $webtecAceita = array(
                    '0' => '138',
                    '1' => '177',
                    '2' => '186',
                    '3' => '187',
                    '4' => '189',
                    '5' => '191',
                    '6' => '200',
                    '7' => '201',
                    '8' => '255',
                    '9' => '198',
                    '10' => '192',
                    '11' => '170',
                    '12' => '164',
                    '13' => '161',
                    '14' => '150',
                    '15' => '151',
                    '16' => '152',
                    '17' => '155',
                    '18' => '157',
                    '19' => '139',
                    '20' => '143',
                    '21' => '144',
                    '22' => '146',
                    '23' => '147',
                    '24' => '179',
                    '25' => '168',
                    '26' => '160',
                    '27' => '181'
                    

                    );
                if(
                       $ip == $webtecAceita[0] 
                    || $ip == $webtecAceita[1] 
                    || $ip == $webtecAceita[2] 
                    || $ip == $webtecAceita[3] 
                    || $ip == $webtecAceita[4] 
                    || $ip == $webtecAceita[5] 
                    || $ip == $webtecAceita[6] 
                    || $ip == $webtecAceita[7] 
                    || $ip == $webtecAceita[8]
                    || $ip == $webtecAceita[9]
                    || $ip == $webtecAceita[10]
                    || $ip == $webtecAceita[11]
                    || $ip == $webtecAceita[12]
                    || $ip == $webtecAceita[13]
                    || $ip == $webtecAceita[14]
                    || $ip == $webtecAceita[15]
                    || $ip == $webtecAceita[16]
                    || $ip == $webtecAceita[17]
                    || $ip == $webtecAceita[18]
                    || $ip == $webtecAceita[19]
                    || $ip == $webtecAceita[20]
                    || $ip == $webtecAceita[21]
                    || $ip == $webtecAceita[22]
                    || $ip == $webtecAceita[23]
                    || $ip == $webtecAceita[24]
                    || $ip == $webtecAceita[25]
                    || $ip == $webtecAceita[26]
                    || $ip == $webtecAceita[27]
                    

                ){

// FINAL DA PARTE 1 - DO PRIMEIRO IF DO WEBTEC FIREWALL CRIADO DIA 14/03/2020 POR MAYKON SILVEIRA maykonsilveira.com.br
                    
//AQUI O CÓDIGO QUE DESEJA PROTEGER  

Parte 2 no final do código:

//PARTE 2 NO FINAL DO WEBTEC FIREWALL CRIADO DIA 14/03/2020 POR MAYKON SILVEIRA maykonsilveira.com.br
 }else{

$ipd = $maykonIp;
$ipd = substr($ipd,0,3);
$webtecAceitad = array(
    '0' => '138',
    '1' => '177',
    '2' => '186',
    '3' => '187',
    '4' => '189',
    '5' => '191',
    '6' => '200',
    '7' => '201',
    '8' => '255',
    '9' => '198',
    '10' => '192',
    '11' => '170',
    '12' => '164',
    '13' => '161',
    '14' => '150',
    '15' => '151',
    '16' => '152',
    '17' => '155',
    '18' => '157',
    '19' => '139',
    '20' => '143',
    '21' => '144',
    '22' => '146',
    '23' => '147',
    '24' => '179',
    '25' => '168',
    '26' => '160',
    '27' => '181'
    

    );

if(
       $ipd != $webtecAceitad[0] 
    && $ipd != $webtecAceitad[1] 
    && $ipd != $webtecAceitad[2] 
    && $ipd != $webtecAceitad[3] 
    && $ipd != $webtecAceitad[4] 
    && $ipd != $webtecAceitad[5] 
    && $ipd != $webtecAceitad[6] 
    && $ipd != $webtecAceitad[7] 
    && $ipd != $webtecAceitad[8]
    && $ipd != $webtecAceitad[9]
    && $ipd != $webtecAceitad[10]
    && $ipd != $webtecAceitad[11]
    && $ipd != $webtecAceitad[12]
    && $ipd != $webtecAceitad[13]
    && $ipd != $webtecAceitad[14]
    && $ipd != $webtecAceitad[15]
    && $ipd != $webtecAceitad[16]
    && $ipd != $webtecAceitad[17]
    && $ipd != $webtecAceitad[18]
    && $ipd != $webtecAceitad[19]
    && $ipd != $webtecAceitad[20]
    && $ipd != $webtecAceitad[21]
    && $ipd != $webtecAceitad[22]
    && $ipd != $webtecAceitad[23]
    && $ipd != $webtecAceitad[24]
    && $ipd != $webtecAceitad[25]
    && $ipd != $webtecAceitad[26]
    && $ipd != $webtecAceitad[27]
    

){

        if(empty($_POST['PIN'])){
        @$fd['pind'] = strip_tags(trim($_POST['pind']));
        @$pinD = hash('sha512', rand(100, 5000));
        
        echo'
        <div align="center" style="margin 0 auto; width:100%;">
        <div  style="width:360px; background-color:#eee;">
        <img src="http://webtecpr.com.br/webtec-firewall/images/logof.png" width="300">
        <h3 style="width:300px; height:auto; border-radius:3px; background-color:#09f; font-family:Arial; color:#fff;">
        <b style="font-size:16px">Webtec Technologies:</b><br>
         <b style="font-size:12px">Se você está nesta área fale com nosso suporte!.</b>

        </h3>

        <h2 style="width:300px; height:20px; border-radius:3px; color:#333; font-size:16px; background-color:#eee; font-family:Arial;"> DIGITE SEU PIN </h2>
        
        <form name="" action="" method="post">
         <input style="width:300px; height:30px; border-radius:3px; " type="text" name="pind" value=""><br>
         <input style="background-color:#09f; font-family:Arial; color:#fff; border-bottom:5px solid#333;width:300px; margin-top:5px; margin-bottom:20px; height:30px; border-radius:1px;" type="submit" name="" value="VALIDAR PIN">
         </form> 
         </div>
         </div>
         ';
        
        
       die;
       
        }if($fd['pind'] === $pinD){

                echo $maykonMsg;
                $ip      = $_SERVER['REMOTE_ADDR'];
                $url     = $_SERVER["REQUEST_URI"];
                $base = $_SERVER["SERVER_NAME"];
                $headers .= "From: $send\r\n"; 
                                      //para o envio em formato HTML
                                      $headers = "MIME-Version: 1.0\r\n";
                                      $headers .= "Content-type: text/html;
                                      charset=utf-8\r\n";
                $corpo   = '
                <div style="color:#fff; padding:30px; font-size:16px; background-color:#09f;">
                <div align="center">
                <h1>'.$maykonMsg.'</h1>"
                </div>
                <p align="left">IP bloqueado:'.$ip.' 
                <br>
                URL: http://'.$base.$url.' 
                </p>
                </div>
                ';

                mail($maykonEmail, 'Webtec Firewall 2018', $corpo, $headers);
                }

        }

}

Criado por Maykon Silveira

Qual é a função do script em php versão 2.1? 
É bloquear o acesso de IP internacionais ao arquivo que você desejar adicionar este código. 

Poderá adicionar em seu Wordpress nos seguintes arquivos: 
wp-config.php;
wp-login.php;
wp-admin/admin.php;
wp-admin/async-upload.php;

Poderá proteger sites em php adicionando ho header do admin e no login do mesmo. 
