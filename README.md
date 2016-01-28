<html>
  
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script type="text/javascript" src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
    <script type="text/javascript" src="http://netdna.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
    <link href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.3.0/css/font-awesome.min.css"
    rel="stylesheet" type="text/css">
    <link href="SallySuffolk.css" rel="stylesheet" type="text/css">
  </head>
  
  <body bgcolor="#ffffff" background="" marginwidth="0" marginheight="0"
  onload="startAT('1');">
    <div class="section">
      <div class="container text-center">
        <div class="row">
          <div class="col-md-12">
            <h1 class="text-warning">Laura Christy
              <br>Coding the Law: Final Project</h1>
          </div>
        </div>
      </div>
    </div>
    <div class="cover">
      <div class="navbar">
        <div class="container">
          <div class="navbar-header">
            <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbar-ex-collapse">
              <span class="sr-only">Toggle navigation</span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
          </div>
          <div class="collapse navbar-collapse" id="navbar-ex-collapse">
            <ul class="nav navbar-nav navbar-right">
              <li class="active">
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Contacts</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="cover-image" style="background-image : url('https://upload.wikimedia.org/wikipedia/commons/3/3e/USA_09562_Boston_Luca_Galuzzi_2007.jpg')"></div>
    </div>
    <div class="section">
      <div class="container">
        <div class="row">
          <div class="col-md-12"></div>
        </div>
        <div class="row">
          <div class="col-md-6">
            <h1 class="text-warning">Contact Information</h1>
            <h3>Laura Christy
              <br>JD. Candidate 2017</h3>
            <p>120 Tremont St.
              <br>Boston, MA, 02108
              <br>Email: lchristy@suffolk.edu
              <br>
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <p>
              <title>Untitled QnA</title>
              <meta http-equiv="Content-type" content="text/html;charset=UTF-8">
              <meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0;">
              <meta name="apple-mobile-web-app-capable" content="no">
              <meta name="apple-mobile-web-app-status-bar-style" content="black">
              <meta property="og:type" content="website">
              <meta property="og:image" content="">
              <meta http-equiv="X-UA-Compatible" content="IE=edge">
              <link rel="apple-touch-icon" href="http://www.qnamarkup.org/images/QnA_300.png">
              <link rel="stylesheet" href="//code.jquery.com/ui/1.11.1/themes/smoothness/jquery-ui.css">
              <script src="//code.jquery.com/jquery-1.10.2.js"></script>
              <script src="//code.jquery.com/ui/1.11.1/jquery-ui.js"></script>
              <style>
                body {
                		font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;
                	}
                
                	#rawmarkup{
                		display:none;
                	}
                	
                	#QandA img{
                		width:100%;
                	}
                
                	div.main{
                		min-width:300px;
                		max-width:650px;
                		margin: 0 auto;
                	padding:0 5px 0 5px;
                		}
                	div.frame{
                		float:left;
                		width:100%;
                		margin:5px 0 5px 0;
                	}
                	div.full{
                		float:left;
                		width:100%;
                	}
                	.button{
                		padding:8px;
                		margin:8px 0 0px 0;
                		width:100%;
                	}
                	div.question_text{
                		float:left;
                		font-family: Verdana, Geneva, sans-serif;
                		font-size: 14px;
                		line-height: 20px;
                		color:#ffffff;
                		min-width:30px;
                		background:#5489eb;
                		border-radius: 15px;
                		padding:10px 15px 14px 15px;
                		margin-right:45px;
                	}
                
                	div.question_text a:link, div.question_text a:hover, div.question_text a:active, div.question_text a:visited{ color:#e3fbfc; } 
                
                	div.question_arrow{
                		float:left; 
                		width: 0; 
                		height: 0; 
                		border-left: 5px solid transparent; 
                		border-right: 10px solid transparent; 
                		border-top: 15px solid #5489eb;
                		margin:0 20px;
                	}
                	div.ans_text{
                		float:right;
                		font-family: Verdana, Geneva, sans-serif;
                		font-size: 14px;
                		line-height: 20px;
                		color:#000000;
                		min-width:30px;
                		background:#eeeeee;
                		border-radius: 15px;
                		padding:10px 15px 14px 15px;
                		margin-left:45px;
                	}
                	div.ans_arrow{
                		float:right; 
                		width: 0; 
                		height: 0; 
                		border-left: 10px solid transparent; 
                		border-right: 5px solid transparent; 
                		border-top: 15px solid #eeeeee;
                		margin:0 20px;
                	}
                	div.choices{
                		float:left;
                		width:100%;
                		margin:15px 0 0 0;
                	}
                	div.credits{
                		float:left;
                		dispaly:none;
                		width:100%;
                		background:#eee;
                		margin:0px 0 15px 0;
                	}
                	div.credit_text{
                		font-family: Verdana, Geneva, sans-serif;
                		font-size: 14px;
                		line-height: 20px;
                		padding:4px 15px 10px 15px;
                	}
                	li.error{
                		list-style-type: none;
                		background:#ffdddd;
                		margin: 10px 0 0 0;
                		padding: 5px;
                	}
                
                	.qpad {
                		float:left;
                		padding:0 15px;
                	}
                
                	a.qabutton {
                		float:left;
                		font-family: Verdana, Geneva, sans-serif;
                		font-size: 14px;
                		line-height: 20px;
                		width:100%;
                		background: #eee;
                		border-radius: 8px;
                		padding:10px 0px 12px 0;
                		margin: 0 0 8px 0;
                		border: solid 1px #888;
                		text-align:left;
                		color: #000000;
                		text-decoration: none;
                	}
                
                	a.qabutton:hover, a.qabutton:active {
                		float:left;
                		font-family: Verdana, Geneva, sans-serif;
                		font-size: 14px;
                		line-height: 20px;
                		width:100%;
                		background: #ddd;
                		border-radius: 8px;
                		padding:10px 0px 12px 0;
                		margin: 0 0 8px 0;
                		border: solid 1px #888;
                		text-align:left;
                		color: #000000;
                		text-decoration: underline;
                	}
                	
                
                	div.xdiv {
                		float:left;
                		width:100%;
                		margin: 0 0 8px 0;
                		background: #eee;
                		border: solid 1px #888;
                		border-radius: 8px;
                	}	
                
                	input.xinput {
                		-webkit-box-sizing: border-box; /* Safari/Chrome, other WebKit */
                		-moz-box-sizing: border-box;    /* Firefox, other Gecko */ 
                		box-sizing: border-box;         /* Opera/IE 8+ */
                		float:left;
                		width:100%;
                		font-family: Verdana, Geneva, sans-serif;
                		font-size: 14px;
                		line-height: 20px;
                		background: #fff;
                		border-top-left-radius: 8px;
                		border-top-right-radius: 8px;
                		padding:10px 10px 12px 10px;
                		border: solid 0px #888;
                		border-bottom: solid 1px #888;
                		text-align:left;
                		color: #000000;
                		text-decoration: none;
                	}
                	
                	a.xbutton {
                		float:left;
                		width:100%;
                		text-align:left;
                		font-family: Verdana, Geneva, sans-serif;
                		font-size: 14px;
                		line-height: 20px;
                		background: #eee;
                		border-radius: 8px;
                		padding:10px 0px 12px 0px;
                		color: #000000;
                		text-decoration: none;
                	}
                	
                	a.xbutton:hover, a.xbutton:active {
                		border-top-left-radius: 0px;
                		border-top-right-radius: 0px;
                		background: #ddd;
                	}
              </style>
            </p>
            <form name="FORM" id="FORM">
              <div id="conversation" style="margin:15px auto 0 auto;padding:0 15px;max-width:500px">
                <div id="QandA" class="QandA">
                  <div style="padding:15px;background:#ddffdd;text-align:center;">Loading QnA...</div>
                </div>
                <div id="Choices" class="choices"></div>
                <div id="rawmarkup" style="display:none;">Q(1):Are debt collectors harassing you? A:Yes Q(1.1):Is the debt collector
                  harassing you an original creditor? Meaning, are they the person or company
                  you originally agreed to pay? A:Yes Q(1.1.1):Unfortunately, the Federal
                  Fair Debt Collection Practices Act does not apply to "original creditors."
                  A:No Q(1.1.2):Are they threatening to take your possessions to pay off
                  the debt? A:Yes Q(1.1.2.1):Debt collectors cannot do this, they can only
                  take items that "secure" your debt. These are items that you agreed could
                  be taken if you do not make payments. Are debt collectors threatening to
                  take secured items? A:Yes Q(1.1.2.1.1): Debt collectors can only threaten
                  to take secured items if they plan on doing it. Debt collectors do not
                  need to go to court to take secured items. GOTO:2 A:No Q(1.1.2.1.2):GOTO:2
                  A:Go back Q(1.1.2.1.3):GOTO:1.1.2 A:Go back Q(1.1.2.2):GOTO:1.1 A:No Q:GOTO:2
                  A:Go Back Q(1.1.3):GOTO:1 A:No Q(1.2):Great! This questionnaire will not
                  be helpful for you. A:Go straight to making a cease and desist letter.
                  Q(1.3):GOTO:6 Q(2): Do you want to know what a debt collector must disclose
                  to you the first time they call? A:Yes Q(2.1):The amount of the debt,&lt;br&gt;&lt;br&gt;Who
                  you owe the money to,&lt;br&gt;&lt;br&gt;AND, you have 30 days to: disagree
                  with the debt, ask for proof, and find out who the original creditor is.
                  A:No Q(2.2):GOTO:3 Q(3):Did the debt collector give you all the information
                  they were supposed to? A:Yes Q(3.1):Great! They complied with this part
                  of the Act. GOTO:4 A:No Q(3.2):If they did not give you all the information
                  they are required to, then they must send you a letter within 5 days. GOTO:4
                  Q(4):Do you want to dispute the debt? A:Yes Q(4.1):If you dispute the debt
                  within 30 days, the debt collector must stop all collection actions until
                  they have given you proof of that debt. GOTO:5 A:No Q(4.2):GOTO:5 Q(5):Do
                  you want to stop the debt collector from contacting you? A:Yes Q(5.1):
                  If you write a cease and desist letter, the debt collector must stop contacting
                  you once they receive it. They may write to you if they will not contact
                  you again, to tell you if they have to take a secured item, or take you
                  to court.GOTO:6 A:No Q(5.2): Are you sure? A:Yes Q(5.2.1): Ok, I hope this
                  information was helpful. A:No Q(5.2.2):GOTO:6 Q(6):Do you want to write
                  a cease and desist letter? A:Yes Q(6.1):What is your name? X:name Q(6.1.1):What
                  is your address? X:address Q(6.1.1.1):What is the debt collector's name?
                  X:creditorname Q(6.1.1.1.1):What is the debt collector's address? X:creditoraddress
                  Q(6.1.1.1.1.1):What is the date? X:date Q(6.1.1.1.1.1.1):What is the account
                  number in question? X:account Q(6.1.1.1.1.1.1.1):GOTO:7 A:No Q(6.2):GOTO:5.2.1
                  DOC(7): &lt;P ALIGN=RIGHT&gt;&lt;x&gt;name&lt;/x&gt;&lt;/p&gt; &lt;P ALIGN=RIGHT&gt;&lt;x&gt;address&lt;/x&gt;&lt;/p&gt;
                  &lt;x&gt;creditorname&lt;/x&gt;&lt;br&gt;&lt;br&gt; &lt;x&gt;creditoraddress&lt;/x&gt;&lt;br&gt;&lt;br&gt;
                  &lt;x&gt;date&lt;/x&gt;&lt;br&gt;&lt;br&gt; RE: Cease and Desist Collection
                  attempts regarding account number &lt;x&gt;account&lt;/x&gt;&lt;br&gt;&lt;br&gt;
                  Dear &lt;x&gt;creditorname&lt;/x&gt;:&lt;br&gt; Someone from your company
                  contacted me about a debt. Please cease and desist from contacting me or
                  my family by telephone at home, or at work, about this or any related matter.
                  Additionally, in accordance with the Fair Debt Collection Practices Act
                  I am requesting the following information: a) How you calculate the money
                  you say I owe. b) Copies of the papers where I agreed to pay what you say
                  I owe. c) The name of the original creditor. d) Demonstrate that you are
                  licensed in my state, and provide this license number to me. Please provide
                  this letter to the company for whom you are collecting so that they have
                  notice of my demand. This letter is not an acknowledgment that I owe you
                  money.&lt;br&gt;&lt;br&gt; If you do not stop immediately, I may be forced
                  to take legal action.&lt;br&gt;&lt;br&gt; Sincerely,&lt;br&gt;&lt;br&gt;
                  Your signature&lt;br&gt;&lt;br&gt; (&lt;x&gt;name&lt;/x&gt;) Q(7): Would
                  you like to see your letter? A:[javascript:submit2('http://www.qnamarkup.org/doc/parse/html/',
                  'GET', 't', 'Proof read your letter. Print it out, and mail it to the debt
                  collector')] Yes Q(7.1): A: No. Q(7.2): Have a great day.</div>
                <div id="ondeck"
                name="ondeck">
                  <div id="doc" name="doc" style="display:none;"></div>
                  <div id="Q-1" name="Q-1" style="display:none;">Are debt collectors harassing you?</div>
                  <div id="Q-1.1" name="Q-1.1" style="display:none;">Is the debt collector harassing you an original creditor? Meaning, are
                    they the person or company you originally agreed to pay?</div>
                  <div id="Q-1.1.1"
                  name="Q-1.1.1" style="display:none;">Unfortunately, the Federal Fair Debt Collection Practices Act does not
                    apply to "original creditors."</div>
                  <div id="Q-1.1.2" name="Q-1.1.2" style="display:none;">Are they threatening to take your possessions to pay off the debt?</div>
                  <div
                  id="Q-1.1.2.1" name="Q-1.1.2.1" style="display:none;">Debt collectors cannot do this, they can only take items that "secure"
                    your debt. These are items that you agreed could be taken if you do not
                    make payments. Are debt collectors threatening to take secured items?</div>
                <div
                id="Q-1.1.2.1.1" name="Q-1.1.2.1.1" style="display:none;">Debt collectors can only threaten to take secured items if they plan on
                  doing it. Debt collectors do not need to go to court to take secured items.
                  GOTO:2</div>
              <div id="Q-1.1.2.1.2" name="Q-1.1.2.1.2" style="display:none;">GOTO:2</div>
              <div id="Q-1.1.2.1.3" name="Q-1.1.2.1.3" style="display:none;">GOTO:1.1.2</div>
              <div id="Q-1.1.2.2" name="Q-1.1.2.2" style="display:none;">GOTO:1.1</div>
              <div id="Q-1.1.2.3" name="Q-1.1.2.3" style="display:none;">GOTO:2</div>
              <div id="Q-1.1.3" name="Q-1.1.3" style="display:none;">GOTO:1</div>
              <div id="Q-1.2" name="Q-1.2" style="display:none;">Great! This questionnaire will not be helpful for you.</div>
              <div id="Q-1.3"
              name="Q-1.3" style="display:none;">GOTO:6</div>
              <div id="Q-2" name="Q-2" style="display:none;">Do you want to know what a debt collector must disclose to you the first
                time they call?</div>
              <div id="Q-2.1" name="Q-2.1" style="display:none;">The amount of the debt,
                <br>
                <br>Who you owe the money to,
                <br>
                <br>AND, you have 30 days to: disagree with the debt, ask for proof, and find
                out who the original creditor is.</div>
              <div id="Q-2.2" name="Q-2.2" style="display:none;">GOTO:3</div>
              <div id="Q-3" name="Q-3" style="display:none;">Did the debt collector give you all the information they were supposed
                to?</div>
              <div id="Q-3.1" name="Q-3.1" style="display:none;">Great! They complied with this part of the Act. GOTO:4</div>
              <div id="Q-3.2"
              name="Q-3.2" style="display:none;">If they did not give you all the information they are required to, then
                they must send you a letter within 5 days. GOTO:4</div>
              <div id="Q-4" name="Q-4"
              style="display:none;">Do you want to dispute the debt?</div>
              <div id="Q-4.1" name="Q-4.1" style="display:none;">If you dispute the debt within 30 days, the debt collector must stop all
                collection actions until they have given you proof of that debt. GOTO:5</div>
              <div
              id="Q-4.2" name="Q-4.2" style="display:none;">GOTO:5</div>
          <div id="Q-5" name="Q-5" style="display:none;">Do you want to stop the debt collector from contacting you?</div>
          <div
          id="Q-5.1" name="Q-5.1" style="display:none;">If you write a cease and desist letter, the debt collector must stop contacting
            you once they receive it. They may write to you if they will not contact
            you again, to tell you if they have to take a secured item, or take you
            to court.GOTO:6</div>
        <div id="Q-5.2" name="Q-5.2" style="display:none;">Are you sure?</div>
        <div id="Q-5.2.1" name="Q-5.2.1" style="display:none;">Ok, I hope this information was helpful.</div>
        <div id="Q-5.2.2" name="Q-5.2.2"
        style="display:none;">GOTO:6</div>
        <div id="Q-6" name="Q-6" style="display:none;">Do you want to write a cease and desist letter?</div>
        <div id="Q-6.1" name="Q-6.1"
        style="display:none;">What is your name?</div>
        <div id="Q-6.1.1" name="Q-6.1.1" style="display:none;">What is your address?</div>
        <div id="Q-6.1.1.1" name="Q-6.1.1.1" style="display:none;">What is the debt collector's name?</div>
        <div id="Q-6.1.1.1.1" name="Q-6.1.1.1.1"
        style="display:none;">What is the debt collector's address?</div>
        <div id="Q-6.1.1.1.1.1" name="Q-6.1.1.1.1.1"
        style="display:none;">What is the date?</div>
        <div id="Q-6.1.1.1.1.1.1" name="Q-6.1.1.1.1.1.1"
        style="display:none;">What is the account number in question?</div>
        <div id="Q-6.1.1.1.1.1.1.1"
        name="Q-6.1.1.1.1.1.1.1" style="display:none;">GOTO:7</div>
        <div id="Q-6.2" name="Q-6.2" style="display:none;">GOTO:5.2.1</div>
        <div id="D-7" name="D-7" style="display:none;">
          <p align="RIGHT">
            <x>name</x>
          </p>
          <p align="RIGHT">
            <x>address</x>
          </p>
          <x>creditorname</x>
          <br>
          <br>
          <x>creditoraddress</x>
          <br>
          <br>
          <x>date</x>
          <br>
          <br>RE: Cease and Desist Collection attempts regarding account number
          <x>account</x>
          <br>
          <br>Dear
          <x>creditorname</x>:
          <br>Someone from your company contacted me about a debt. Please cease and
          desist from contacting me or my family by telephone at home, or at work,
          about this or any related matter. Additionally, in accordance with the
          Fair Debt Collection Practices Act I am requesting the following information:
          a) How you calculate the money you say I owe. b) Copies of the papers where
          I agreed to pay what you say I owe. c) The name of the original creditor.
          d) Demonstrate that you are licensed in my state, and provide this license
          number to me. Please provide this letter to the company for whom you are
          collecting so that they have notice of my demand. This letter is not an
          acknowledgment that I owe you money.
          <br>
          <br>If you do not stop immediately, I may be forced to take legal action.
          <br>
          <br>Sincerely,
          <br>
          <br>Your signature
          <br>
          <br>(
          <x>name</x>)</div>
        <div id="Q-7" name="Q-7" style="display:none;">Would you like to see your letter?</div>
        <div id="Q-7.1" name="Q-7.1" style="display:none;"></div>
        <div id="Q-7.2" name="Q-7.2" style="display:none;">Have a great day.</div>
        <div id="A-1.1" name="A-1.1" style="display:none;">Yes</div>
        <div id="A-href-1.1" name="A-href-1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1" name="A-target-1.1" style="display:none;"></div>
        <div id="X-1.1" name="X-1.1" style="display:none;"></div>
        <div id="A-1.1.1" name="A-1.1.1" style="display:none;">Yes</div>
        <div id="A-href-1.1.1" name="A-href-1.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.1" name="A-target-1.1.1"
        style="display:none;"></div>
        <div id="X-1.1.1" name="X-1.1.1" style="display:none;"></div>
        <div id="A-1.1.2" name="A-1.1.2" style="display:none;">No</div>
        <div id="A-href-1.1.2" name="A-href-1.1.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.2" name="A-target-1.1.2"
        style="display:none;"></div>
        <div id="X-1.1.2" name="X-1.1.2" style="display:none;"></div>
        <div id="A-1.1.2.1" name="A-1.1.2.1" style="display:none;">Yes</div>
        <div id="A-href-1.1.2.1" name="A-href-1.1.2.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.2.1" name="A-target-1.1.2.1"
        style="display:none;"></div>
        <div id="X-1.1.2.1" name="X-1.1.2.1" style="display:none;"></div>
        <div id="A-1.1.2.1.1" name="A-1.1.2.1.1" style="display:none;">Yes</div>
        <div id="A-href-1.1.2.1.1" name="A-href-1.1.2.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.2.1.1" name="A-target-1.1.2.1.1"
        style="display:none;"></div>
        <div id="X-1.1.2.1.1" name="X-1.1.2.1.1" style="display:none;"></div>
        <div id="A-1.1.2.1.2" name="A-1.1.2.1.2" style="display:none;">No</div>
        <div id="A-href-1.1.2.1.2" name="A-href-1.1.2.1.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.2.1.2" name="A-target-1.1.2.1.2"
        style="display:none;"></div>
        <div id="X-1.1.2.1.2" name="X-1.1.2.1.2" style="display:none;"></div>
        <div id="A-1.1.2.1.3" name="A-1.1.2.1.3" style="display:none;">Go back</div>
        <div id="A-href-1.1.2.1.3" name="A-href-1.1.2.1.3" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.2.1.3" name="A-target-1.1.2.1.3"
        style="display:none;"></div>
        <div id="X-1.1.2.1.3" name="X-1.1.2.1.3" style="display:none;"></div>
        <div id="A-1.1.2.2" name="A-1.1.2.2" style="display:none;">Go back</div>
        <div id="A-href-1.1.2.2" name="A-href-1.1.2.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.2.2" name="A-target-1.1.2.2"
        style="display:none;"></div>
        <div id="X-1.1.2.2" name="X-1.1.2.2" style="display:none;"></div>
        <div id="A-1.1.2.3" name="A-1.1.2.3" style="display:none;">No</div>
        <div id="A-href-1.1.2.3" name="A-href-1.1.2.3" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.2.3" name="A-target-1.1.2.3"
        style="display:none;"></div>
        <div id="X-1.1.2.3" name="X-1.1.2.3" style="display:none;"></div>
        <div id="A-1.1.3" name="A-1.1.3" style="display:none;">Go Back</div>
        <div id="A-href-1.1.3" name="A-href-1.1.3" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.1.3" name="A-target-1.1.3"
        style="display:none;"></div>
        <div id="X-1.1.3" name="X-1.1.3" style="display:none;"></div>
        <div id="A-1.2" name="A-1.2" style="display:none;">No</div>
        <div id="A-href-1.2" name="A-href-1.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.2" name="A-target-1.2" style="display:none;"></div>
        <div id="X-1.2" name="X-1.2" style="display:none;"></div>
        <div id="A-1.3" name="A-1.3" style="display:none;">Go straight to making a cease and desist letter.</div>
        <div id="A-href-1.3"
        name="A-href-1.3" style="display:none;">javascript:void('');</div>
        <div id="A-target-1.3" name="A-target-1.3" style="display:none;"></div>
        <div id="X-1.3" name="X-1.3" style="display:none;"></div>
        <div id="A-2.1" name="A-2.1" style="display:none;">Yes</div>
        <div id="A-href-2.1" name="A-href-2.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-2.1" name="A-target-2.1" style="display:none;"></div>
        <div id="X-2.1" name="X-2.1" style="display:none;"></div>
        <div id="A-2.2" name="A-2.2" style="display:none;">No</div>
        <div id="A-href-2.2" name="A-href-2.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-2.2" name="A-target-2.2" style="display:none;"></div>
        <div id="X-2.2" name="X-2.2" style="display:none;"></div>
        <div id="A-3.1" name="A-3.1" style="display:none;">Yes</div>
        <div id="A-href-3.1" name="A-href-3.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-3.1" name="A-target-3.1" style="display:none;"></div>
        <div id="X-3.1" name="X-3.1" style="display:none;"></div>
        <div id="A-3.2" name="A-3.2" style="display:none;">No</div>
        <div id="A-href-3.2" name="A-href-3.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-3.2" name="A-target-3.2" style="display:none;"></div>
        <div id="X-3.2" name="X-3.2" style="display:none;"></div>
        <div id="A-4.1" name="A-4.1" style="display:none;">Yes</div>
        <div id="A-href-4.1" name="A-href-4.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-4.1" name="A-target-4.1" style="display:none;"></div>
        <div id="X-4.1" name="X-4.1" style="display:none;"></div>
        <div id="A-4.2" name="A-4.2" style="display:none;">No</div>
        <div id="A-href-4.2" name="A-href-4.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-4.2" name="A-target-4.2" style="display:none;"></div>
        <div id="X-4.2" name="X-4.2" style="display:none;"></div>
        <div id="A-5.1" name="A-5.1" style="display:none;">Yes</div>
        <div id="A-href-5.1" name="A-href-5.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-5.1" name="A-target-5.1" style="display:none;"></div>
        <div id="X-5.1" name="X-5.1" style="display:none;"></div>
        <div id="A-5.2" name="A-5.2" style="display:none;">No</div>
        <div id="A-href-5.2" name="A-href-5.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-5.2" name="A-target-5.2" style="display:none;"></div>
        <div id="X-5.2" name="X-5.2" style="display:none;"></div>
        <div id="A-5.2.1" name="A-5.2.1" style="display:none;">Yes</div>
        <div id="A-href-5.2.1" name="A-href-5.2.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-5.2.1" name="A-target-5.2.1"
        style="display:none;"></div>
        <div id="X-5.2.1" name="X-5.2.1" style="display:none;"></div>
        <div id="A-5.2.2" name="A-5.2.2" style="display:none;">No</div>
        <div id="A-href-5.2.2" name="A-href-5.2.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-5.2.2" name="A-target-5.2.2"
        style="display:none;"></div>
        <div id="X-5.2.2" name="X-5.2.2" style="display:none;"></div>
        <div id="A-6.1" name="A-6.1" style="display:none;">Yes</div>
        <div id="A-href-6.1" name="A-href-6.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.1" name="A-target-6.1" style="display:none;"></div>
        <div id="X-6.1" name="X-6.1" style="display:none;"></div>
        <div id="A-6.1.1" name="A-6.1.1" style="display:none;">
          <variable></variable>
        </div>
        <div id="A-href-6.1.1" name="A-href-6.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.1.1" name="A-target-6.1.1"
        style="display:none;"></div>
        <div id="X-6.1.1" name="X-6.1.1" style="display:none;">name</div>
        <div id="A-6.1.1.1" name="A-6.1.1.1" style="display:none;">
          <variable></variable>
        </div>
        <div id="A-href-6.1.1.1" name="A-href-6.1.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.1.1.1" name="A-target-6.1.1.1"
        style="display:none;"></div>
        <div id="X-6.1.1.1" name="X-6.1.1.1" style="display:none;">address</div>
        <div id="A-6.1.1.1.1" name="A-6.1.1.1.1" style="display:none;">
          <variable></variable>
        </div>
        <div id="A-href-6.1.1.1.1" name="A-href-6.1.1.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.1.1.1.1" name="A-target-6.1.1.1.1"
        style="display:none;"></div>
        <div id="X-6.1.1.1.1" name="X-6.1.1.1.1" style="display:none;">creditorname</div>
        <div id="A-6.1.1.1.1.1" name="A-6.1.1.1.1.1" style="display:none;">
          <variable></variable>
        </div>
        <div id="A-href-6.1.1.1.1.1" name="A-href-6.1.1.1.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.1.1.1.1.1" name="A-target-6.1.1.1.1.1"
        style="display:none;"></div>
        <div id="X-6.1.1.1.1.1" name="X-6.1.1.1.1.1" style="display:none;">creditoraddress</div>
        <div id="A-6.1.1.1.1.1.1" name="A-6.1.1.1.1.1.1"
        style="display:none;">
          <variable></variable>
        </div>
        <div id="A-href-6.1.1.1.1.1.1" name="A-href-6.1.1.1.1.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.1.1.1.1.1.1" name="A-target-6.1.1.1.1.1.1"
        style="display:none;"></div>
        <div id="X-6.1.1.1.1.1.1" name="X-6.1.1.1.1.1.1" style="display:none;">date</div>
        <div id="A-6.1.1.1.1.1.1.1" name="A-6.1.1.1.1.1.1.1" style="display:none;">
          <variable></variable>
        </div>
        <div id="A-href-6.1.1.1.1.1.1.1" name="A-href-6.1.1.1.1.1.1.1" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.1.1.1.1.1.1.1" name="A-target-6.1.1.1.1.1.1.1"
        style="display:none;"></div>
        <div id="X-6.1.1.1.1.1.1.1" name="X-6.1.1.1.1.1.1.1" style="display:none;">account</div>
        <div id="A-6.2" name="A-6.2" style="display:none;">No</div>
        <div id="A-href-6.2" name="A-href-6.2" style="display:none;">javascript:void('');</div>
        <div id="A-target-6.2" name="A-target-6.2" style="display:none;"></div>
        <div id="X-6.2" name="X-6.2" style="display:none;"></div>
        <div id="A-7.1" name="A-7.1" style="display:none;">Yes</div>
        <div id="A-href-7.1" name="A-href-7.1" style="display:none;">javascript:submit2('http://www.qnamarkup.org/doc/parse/html/', 'GET',
          't', 'Proof read your letter. Print it out, and mail it to the debt collector')</div>
        <div
        id="A-target-7.1" name="A-target-7.1" style="display:none;">target="_blank"</div>
      <div id="X-7.1" name="X-7.1" style="display:none;"></div>
      <div id="A-7.2" name="A-7.2" style="display:none;">No.</div>
      <div id="A-href-7.2" name="A-href-7.2" style="display:none;">javascript:void('');</div>
      <div id="A-target-7.2" name="A-target-7.2" style="display:none;"></div>
      <div id="X-7.2" name="X-7.2" style="display:none;"></div>
    </div>
    <textarea id="original" name="original" style="display:none;" disabled="disabled">&lt;div id="doc" name="doc" style="display:none;"&gt;&lt;/div&gt;&lt;div
      id='Q-1' name='Q-1' style='display:none;'&gt;Are debt collectors harassing
      you? &lt;/div&gt;&lt;div id='Q-1.1' name='Q-1.1' style='display:none;'&gt;Is
      the debt collector harassing you an original creditor? Meaning, are they
      the person or company you originally agreed to pay? &lt;/div&gt;&lt;div
      id='Q-1.1.1' name='Q-1.1.1' style='display:none;'&gt;Unfortunately, the
      Federal Fair Debt Collection Practices Act does not apply to "original
      creditors." &lt;/div&gt;&lt;div id='Q-1.1.2' name='Q-1.1.2' style='display:none;'&gt;Are
      they threatening to take your possessions to pay off the debt? &lt;/div&gt;&lt;div
      id='Q-1.1.2.1' name='Q-1.1.2.1' style='display:none;'&gt;Debt collectors
      cannot do this, they can only take items that "secure" your debt. These
      are items that you agreed could be taken if you do not make payments. Are
      debt collectors threatening to take secured items? &lt;/div&gt;&lt;div
      id='Q-1.1.2.1.1' name='Q-1.1.2.1.1' style='display:none;'&gt; Debt collectors
      can only threaten to take secured items if they plan on doing it. Debt
      collectors do not need to go to court to take secured items. GOTO:2 &lt;/div&gt;&lt;div
      id='Q-1.1.2.1.2' name='Q-1.1.2.1.2' style='display:none;'&gt;GOTO:2 &lt;/div&gt;&lt;div
      id='Q-1.1.2.1.3' name='Q-1.1.2.1.3' style='display:none;'&gt;GOTO:1.1.2
      &lt;/div&gt;&lt;div id='Q-1.1.2.2' name='Q-1.1.2.2' style='display:none;'&gt;GOTO:1.1
      &lt;/div&gt;&lt;div id='Q-1.1.2.3' name='Q-1.1.2.3' style='display:none;'&gt;GOTO:2
      &lt;/div&gt;&lt;div id='Q-1.1.3' name='Q-1.1.3' style='display:none;'&gt;GOTO:1
      &lt;/div&gt;&lt;div id='Q-1.2' name='Q-1.2' style='display:none;'&gt;Great!
      This questionnaire will not be helpful for you. &lt;/div&gt;&lt;div id='Q-1.3'
      name='Q-1.3' style='display:none;'&gt;GOTO:6 &lt;/div&gt;&lt;div id='Q-2'
      name='Q-2' style='display:none;'&gt; Do you want to know what a debt collector
      must disclose to you the first time they call? &lt;/div&gt;&lt;div id='Q-2.1'
      name='Q-2.1' style='display:none;'&gt;The amount of the debt,&lt;br&gt;&lt;br&gt;Who
      you owe the money to,&lt;br&gt;&lt;br&gt;AND, you have 30 days to: disagree
      with the debt, ask for proof, and find out who the original creditor is.
      &lt;/div&gt;&lt;div id='Q-2.2' name='Q-2.2' style='display:none;'&gt;GOTO:3
      &lt;/div&gt;&lt;div id='Q-3' name='Q-3' style='display:none;'&gt;Did the
      debt collector give you all the information they were supposed to? &lt;/div&gt;&lt;div
      id='Q-3.1' name='Q-3.1' style='display:none;'&gt;Great! They complied with
      this part of the Act. GOTO:4 &lt;/div&gt;&lt;div id='Q-3.2' name='Q-3.2'
      style='display:none;'&gt;If they did not give you all the information they
      are required to, then they must send you a letter within 5 days. GOTO:4
      &lt;/div&gt;&lt;div id='Q-4' name='Q-4' style='display:none;'&gt;Do you
      want to dispute the debt? &lt;/div&gt;&lt;div id='Q-4.1' name='Q-4.1' style='display:none;'&gt;If
      you dispute the debt within 30 days, the debt collector must stop all collection
      actions until they have given you proof of that debt. GOTO:5 &lt;/div&gt;&lt;div
      id='Q-4.2' name='Q-4.2' style='display:none;'&gt;GOTO:5 &lt;/div&gt;&lt;div
      id='Q-5' name='Q-5' style='display:none;'&gt;Do you want to stop the debt
      collector from contacting you? &lt;/div&gt;&lt;div id='Q-5.1' name='Q-5.1'
      style='display:none;'&gt; If you write a cease and desist letter, the debt
      collector must stop contacting you once they receive it. They may write
      to you if they will not contact you again, to tell you if they have to
      take a secured item, or take you to court.GOTO:6 &lt;/div&gt;&lt;div id='Q-5.2'
      name='Q-5.2' style='display:none;'&gt; Are you sure? &lt;/div&gt;&lt;div
      id='Q-5.2.1' name='Q-5.2.1' style='display:none;'&gt; Ok, I hope this information
      was helpful. &lt;/div&gt;&lt;div id='Q-5.2.2' name='Q-5.2.2' style='display:none;'&gt;GOTO:6
      &lt;/div&gt;&lt;div id='Q-6' name='Q-6' style='display:none;'&gt;Do you
      want to write a cease and desist letter? &lt;/div&gt;&lt;div id='Q-6.1'
      name='Q-6.1' style='display:none;'&gt;What is your name? &lt;/div&gt;&lt;div
      id='Q-6.1.1' name='Q-6.1.1' style='display:none;'&gt;What is your address?
      &lt;/div&gt;&lt;div id='Q-6.1.1.1' name='Q-6.1.1.1' style='display:none;'&gt;What
      is the debt collector's name? &lt;/div&gt;&lt;div id='Q-6.1.1.1.1' name='Q-6.1.1.1.1'
      style='display:none;'&gt;What is the debt collector's address? &lt;/div&gt;&lt;div
      id='Q-6.1.1.1.1.1' name='Q-6.1.1.1.1.1' style='display:none;'&gt;What is
      the date? &lt;/div&gt;&lt;div id='Q-6.1.1.1.1.1.1' name='Q-6.1.1.1.1.1.1'
      style='display:none;'&gt;What is the account number in question? &lt;/div&gt;&lt;div
      id='Q-6.1.1.1.1.1.1.1' name='Q-6.1.1.1.1.1.1.1' style='display:none;'&gt;GOTO:7
      &lt;/div&gt;&lt;div id='Q-6.2' name='Q-6.2' style='display:none;'&gt;GOTO:5.2.1
      &lt;/div&gt;&lt;div id='D-7' name='D-7' style='display:none;'&gt; &lt;P
      ALIGN=RIGHT&gt;&lt;x&gt;name&lt;/x&gt;&lt;/p&gt; &lt;P ALIGN=RIGHT&gt;&lt;x&gt;address&lt;/x&gt;&lt;/p&gt;
      &lt;x&gt;creditorname&lt;/x&gt;&lt;br&gt;&lt;br&gt; &lt;x&gt;creditoraddress&lt;/x&gt;&lt;br&gt;&lt;br&gt;
      &lt;x&gt;date&lt;/x&gt;&lt;br&gt;&lt;br&gt; RE: Cease and Desist Collection
      attempts regarding account number &lt;x&gt;account&lt;/x&gt;&lt;br&gt;&lt;br&gt;
      Dear &lt;x&gt;creditorname&lt;/x&gt;:&lt;br&gt; Someone from your company
      contacted me about a debt. Please cease and desist from contacting me or
      my family by telephone at home, or at work, about this or any related matter.
      Additionally, in accordance with the Fair Debt Collection Practices Act
      I am requesting the following information: a) How you calculate the money
      you say I owe. b) Copies of the papers where I agreed to pay what you say
      I owe. c) The name of the original creditor. d) Demonstrate that you are
      licensed in my state, and provide this license number to me. Please provide
      this letter to the company for whom you are collecting so that they have
      notice of my demand. This letter is not an acknowledgment that I owe you
      money.&lt;br&gt;&lt;br&gt; If you do not stop immediately, I may be forced
      to take legal action.&lt;br&gt;&lt;br&gt; Sincerely,&lt;br&gt;&lt;br&gt;
      Your signature&lt;br&gt;&lt;br&gt; (&lt;x&gt;name&lt;/x&gt;) &lt;/div&gt;&lt;div
      id='Q-7' name='Q-7' style='display:none;'&gt; Would you like to see your
      letter? &lt;/div&gt;&lt;div id='Q-7.1' name='Q-7.1' style='display:none;'&gt;
      &lt;/div&gt;&lt;div id='Q-7.2' name='Q-7.2' style='display:none;'&gt; Have
      a great day.&lt;/div&gt;&lt;div id='A-1.1' name='A-1.1' style='display:none;'&gt;Yes
      &lt;/div&gt;&lt;div id='A-href-1.1' name='A-href-1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1' name='A-target-1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1' name='X-1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-1.1.1'
      name='A-1.1.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div id='A-href-1.1.1'
      name='A-href-1.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.1' name='A-target-1.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.1' name='X-1.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.2' name='A-1.1.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div
      id='A-href-1.1.2' name='A-href-1.1.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.2' name='A-target-1.1.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.2' name='X-1.1.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.2.1' name='A-1.1.2.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div
      id='A-href-1.1.2.1' name='A-href-1.1.2.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.2.1' name='A-target-1.1.2.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.2.1' name='X-1.1.2.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.2.1.1' name='A-1.1.2.1.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div
      id='A-href-1.1.2.1.1' name='A-href-1.1.2.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.2.1.1' name='A-target-1.1.2.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.2.1.1' name='X-1.1.2.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.2.1.2' name='A-1.1.2.1.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div
      id='A-href-1.1.2.1.2' name='A-href-1.1.2.1.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.2.1.2' name='A-target-1.1.2.1.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.2.1.2' name='X-1.1.2.1.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.2.1.3' name='A-1.1.2.1.3' style='display:none;'&gt;Go back &lt;/div&gt;&lt;div
      id='A-href-1.1.2.1.3' name='A-href-1.1.2.1.3' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.2.1.3' name='A-target-1.1.2.1.3' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.2.1.3' name='X-1.1.2.1.3' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.2.2' name='A-1.1.2.2' style='display:none;'&gt;Go back &lt;/div&gt;&lt;div
      id='A-href-1.1.2.2' name='A-href-1.1.2.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.2.2' name='A-target-1.1.2.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.2.2' name='X-1.1.2.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.2.3' name='A-1.1.2.3' style='display:none;'&gt;No &lt;/div&gt;&lt;div
      id='A-href-1.1.2.3' name='A-href-1.1.2.3' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.2.3' name='A-target-1.1.2.3' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.2.3' name='X-1.1.2.3' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.1.3' name='A-1.1.3' style='display:none;'&gt;Go Back &lt;/div&gt;&lt;div
      id='A-href-1.1.3' name='A-href-1.1.3' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.1.3' name='A-target-1.1.3' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.1.3' name='X-1.1.3' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-1.2' name='A-1.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div
      id='A-href-1.2' name='A-href-1.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.2' name='A-target-1.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.2' name='X-1.2' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-1.3'
      name='A-1.3' style='display:none;'&gt;Go straight to making a cease and
      desist letter. &lt;/div&gt;&lt;div id='A-href-1.3' name='A-href-1.3' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-1.3' name='A-target-1.3' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-1.3' name='X-1.3' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-2.1'
      name='A-2.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div id='A-href-2.1'
      name='A-href-2.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-2.1' name='A-target-2.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-2.1' name='X-2.1' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-2.2'
      name='A-2.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div id='A-href-2.2'
      name='A-href-2.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-2.2' name='A-target-2.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-2.2' name='X-2.2' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-3.1'
      name='A-3.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div id='A-href-3.1'
      name='A-href-3.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-3.1' name='A-target-3.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-3.1' name='X-3.1' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-3.2'
      name='A-3.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div id='A-href-3.2'
      name='A-href-3.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-3.2' name='A-target-3.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-3.2' name='X-3.2' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-4.1'
      name='A-4.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div id='A-href-4.1'
      name='A-href-4.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-4.1' name='A-target-4.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-4.1' name='X-4.1' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-4.2'
      name='A-4.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div id='A-href-4.2'
      name='A-href-4.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-4.2' name='A-target-4.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-4.2' name='X-4.2' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-5.1'
      name='A-5.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div id='A-href-5.1'
      name='A-href-5.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-5.1' name='A-target-5.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-5.1' name='X-5.1' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-5.2'
      name='A-5.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div id='A-href-5.2'
      name='A-href-5.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-5.2' name='A-target-5.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-5.2' name='X-5.2' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-5.2.1'
      name='A-5.2.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div id='A-href-5.2.1'
      name='A-href-5.2.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-5.2.1' name='A-target-5.2.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-5.2.1' name='X-5.2.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-5.2.2' name='A-5.2.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div
      id='A-href-5.2.2' name='A-href-5.2.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-5.2.2' name='A-target-5.2.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-5.2.2' name='X-5.2.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='A-6.1' name='A-6.1' style='display:none;'&gt;Yes &lt;/div&gt;&lt;div
      id='A-href-6.1' name='A-href-6.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.1' name='A-target-6.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.1' name='X-6.1' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-6.1.1'
      name='A-6.1.1' style='display:none;'&gt;&lt;variable&gt;&lt;/div&gt;&lt;div
      id='A-href-6.1.1' name='A-href-6.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.1.1' name='A-target-6.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.1.1' name='X-6.1.1' style='display:none;'&gt;name&lt;/div&gt;&lt;div
      id='A-6.1.1.1' name='A-6.1.1.1' style='display:none;'&gt;&lt;variable&gt;&lt;/div&gt;&lt;div
      id='A-href-6.1.1.1' name='A-href-6.1.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.1.1.1' name='A-target-6.1.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.1.1.1' name='X-6.1.1.1' style='display:none;'&gt;address&lt;/div&gt;&lt;div
      id='A-6.1.1.1.1' name='A-6.1.1.1.1' style='display:none;'&gt;&lt;variable&gt;&lt;/div&gt;&lt;div
      id='A-href-6.1.1.1.1' name='A-href-6.1.1.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.1.1.1.1' name='A-target-6.1.1.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.1.1.1.1' name='X-6.1.1.1.1' style='display:none;'&gt;creditorname&lt;/div&gt;&lt;div
      id='A-6.1.1.1.1.1' name='A-6.1.1.1.1.1' style='display:none;'&gt;&lt;variable&gt;&lt;/div&gt;&lt;div
      id='A-href-6.1.1.1.1.1' name='A-href-6.1.1.1.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.1.1.1.1.1' name='A-target-6.1.1.1.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.1.1.1.1.1' name='X-6.1.1.1.1.1' style='display:none;'&gt;creditoraddress&lt;/div&gt;&lt;div
      id='A-6.1.1.1.1.1.1' name='A-6.1.1.1.1.1.1' style='display:none;'&gt;&lt;variable&gt;&lt;/div&gt;&lt;div
      id='A-href-6.1.1.1.1.1.1' name='A-href-6.1.1.1.1.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.1.1.1.1.1.1' name='A-target-6.1.1.1.1.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.1.1.1.1.1.1' name='X-6.1.1.1.1.1.1' style='display:none;'&gt;date&lt;/div&gt;&lt;div
      id='A-6.1.1.1.1.1.1.1' name='A-6.1.1.1.1.1.1.1' style='display:none;'&gt;&lt;variable&gt;&lt;/div&gt;&lt;div
      id='A-href-6.1.1.1.1.1.1.1' name='A-href-6.1.1.1.1.1.1.1' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.1.1.1.1.1.1.1' name='A-target-6.1.1.1.1.1.1.1' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.1.1.1.1.1.1.1' name='X-6.1.1.1.1.1.1.1' style='display:none;'&gt;account&lt;/div&gt;&lt;div
      id='A-6.2' name='A-6.2' style='display:none;'&gt;No &lt;/div&gt;&lt;div
      id='A-href-6.2' name='A-href-6.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-6.2' name='A-target-6.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-6.2' name='X-6.2' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-7.1'
      name='A-7.1' style='display:none;'&gt; Yes &lt;/div&gt;&lt;div id='A-href-7.1'
      name='A-href-7.1' style='display:none;'&gt;javascript:submit2('http://www.qnamarkup.org/doc/parse/html/',
      'GET', 't', 'Proof read your letter. Print it out, and mail it to the debt
      collector')&lt;/div&gt;&lt;div id='A-target-7.1' name='A-target-7.1' style='display:none;'&gt;target="_blank"&lt;/div&gt;&lt;div
      id='X-7.1' name='X-7.1' style='display:none;'&gt;&lt;/div&gt;&lt;div id='A-7.2'
      name='A-7.2' style='display:none;'&gt; No. &lt;/div&gt;&lt;div id='A-href-7.2'
      name='A-href-7.2' style='display:none;'&gt;javascript:void('');&lt;/div&gt;&lt;div
      id='A-target-7.2' name='A-target-7.2' style='display:none;'&gt;&lt;/div&gt;&lt;div
      id='X-7.2' name='X-7.2' style='display:none;'&gt;&lt;/div&gt;</textarea>
    <textarea
    id="transcript" name="transcript" style="display:none;" disabled="disabled"></textarea>
      <div style="float:left;width:100%;margin:15px 0 0px 0;border-top: solid 1px #ddd;">
        <div id="credits" class="credits" style="display:none;">
          <div class="credit_text"></div>
        </div>
        <p align="center">
          <a href="http://www.qnamarkup.org/" target="_top">code your own</a>
        </p>
      </div>
      </div>
      </form>
      </div>
      <script type="text/javascript">
        var QNum = 0;
        	var Qhtml = "";
        	var Dhtml = "";
        	var label = "";
        	var GOTOfired = 0;
        
        	$("#conversation input").on("keypress", 'form', function (e) {
            	var code = e.keyCode || e.which;
            	if (code == 13) {
                	e.preventDefault();
                	return false;
            	}
        	});
        
        	function answerQ(lb,restart) {
        		label = lb;
        		Dhtml = 'D-'+label;
        		Qhtml = 'Q-'+label;
        		var Ahtml = 'A-'+label;
        		var Jhtml = 'J-'+QNum;
        		var Xhtml = 'X-'+label;
        		var Xihtml = 'Xi-'+label;
        		
        		var input_error = 0;
        		if (restart == undefined) {
        			var regexp = new RegExp("\<variable\>");
        			if (document.getElementById(Ahtml).innerHTML.match(regexp)) {
        				document.getElementById(Xihtml).value = document.getElementById(Xihtml).value.replace(/(^\s*|\s*$)/,"");
        				if (document.getElementById(Xihtml).value == "") {
        					input_error = "Your answer appears to be empty.";
        				} else {
        					document.getElementById(Xihtml).value = document.getElementById(Xihtml).value.replace(/</g,"&lt;");
        					document.getElementById(Xihtml).value = document.getElementById(Xihtml).value.replace(/>/g,"&gt;");
        				}
        			} 
        		}
        			
        		if (input_error != 0) {
        			alert(input_error);
        			document.getElementById(Xihtml).focus();			
        		} else {
        			if (restart == undefined) {
        				document.getElementById('QandA').innerHTML += "<div class='frame'><div class='full'><div class='ans_text'>"+document.getElementById(Ahtml).innerHTML+"</div></div><div class='ans_arrow'></div></div></div></div>";
        				// insert answer from button
        				if(document.getElementById(Ahtml).innerHTML != "") { document.getElementById('transcript').value += "USER: "+document.getElementById(Ahtml).innerHTML; }
        				if (document.getElementById('QandA').innerHTML.match(regexp)) {
        				 	var duplicatevars = new RegExp("id=\""+document.getElementById(Xhtml).innerHTML+"(.)*"+document.getElementById(Xhtml).innerHTML+"\"","g");
        					document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(duplicatevars, "");
        					document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(/\<variable\>(\<\/variable\>)?/, "<input type=hidden id=\""+document.getElementById(Xhtml).innerHTML+"\" name=\""+document.getElementById(Xhtml).innerHTML+"\" value=\""+document.getElementById(Xihtml).value+"\"/>"+document.getElementById(Xihtml).value);
        					document.getElementById('transcript').value = document.getElementById('transcript').value.replace(/\<variable\>(\<\/variable\>)?/, document.getElementById(Xihtml).value+"\n");
        					var thisvariable = new RegExp("<(X|x)>"+document.getElementById(Xhtml).innerHTML+"<\/(X|x)>","g");
        					document.getElementById('ondeck').innerHTML = document.getElementById('ondeck').innerHTML.replace(thisvariable, document.getElementById(document.getElementById(Xhtml).innerHTML).value);
        					document.getElementById('doc').innerHTML = document.getElementById('doc').innerHTML.replace(thisvariable, document.getElementById(document.getElementById(Xhtml).innerHTML).innerHTML);
        					console.log("thisvariable: "+thisvariable);
        					console.log("Variable name: "+document.getElementById(Xhtml).innerHTML);
        					console.log("Variable value: "+document.getElementById(document.getElementById(Xhtml).innerHTML).value);
        				}
        				document.getElementById('Choices').innerHTML = '';
        				setTimeout(function() {renderQnA(Qhtml,Jhtml,Dhtml,restart)}, 300);
        			} else {
        				document.getElementById('Choices').innerHTML = '';
        				renderQnA(Qhtml,Jhtml,Dhtml,restart);			
        			}
        
        		}
        		
        	}
        
        
        	function renderQnA(Qht,Jht,Dht,restar) {
        		Dhtml = Dht;
        					
        		var GOTOfired = 0;
        		swapGOTO(Qht,Jht);
        
        		if (GOTOfired == 0) {
        			document.getElementById('QandA').innerHTML += "<div id="+Jht+" style=\"float:left;width:100%;height:1px;\">&nbsp;</div>";
        		}
        		document.getElementById('QandA').innerHTML += "<div class='frame'><div class='full'><div class='question_text'>"+ document.getElementById(Qhtml).innerHTML+"</div></div><div class='question_arrow'></div></div>";		
        
        		document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(/(\<br\>){2}/gi,"</div></div><div class='question_arrow'></div></div></div></div><div class='frame'><div class='full'><div class='question_text'>");
        		document.getElementById('QandA').innerHTML = document.getElementById('QandA').innerHTML.replace(/(\<br\> \<br\>)/gi,"<br><br>");
        
        		// add question 
        		document.getElementById('transcript').value += "BOT: "+ document.getElementById(Qhtml).innerHTML;
        		document.getElementById('transcript').value = document.getElementById('transcript').value.replace(/(\<br\>){2}/gi,"\nBOT: ");
        				
        		if (document.getElementById(Dhtml)) {
        			document.getElementById('doc').innerHTML += document.getElementById(Dhtml).innerHTML;
        		}
        						
        		tmp = getElementsByIdRegExp("div", "A-"+label+"(\\.{1}\\d){1}$");
        		a_href = getElementsByIdRegExp("div", "A-href-"+label+"(\\.{1}\\d){1}$");
        		a_target = getElementsByIdRegExp("div", "A-target-"+label+"(\\.{1}\\d){1}$");
        		tmp_x = getElementsByIdRegExp("div", "X-"+label+"(\\.{1}\\d){1}$");
        		var Xishere = 0;
        		for ( var i = 0; i < tmp.length; i++ ) {
        			var nextlabel = tmp[i].id.substr(2);
        			var Xihtml = 'Xi-'+nextlabel;
        			var regexp = "\<variable\>";
        			var regexp_js = "^javascript:";
        			if (tmp[i].innerHTML.match(regexp)) {
        				document.getElementById('Choices').innerHTML += "<div class=\"xdiv\"><input type=\"text\" id=\""+Xihtml+"\" name=\""+Xihtml+"\" class=\"xinput\" onkeypress=\"{if (event.keyCode==13)answerQ('"+nextlabel+"')}\"/><a href=\"javascript:void('');\" class=\"xbutton\" onClick=\"answerQ('"+nextlabel+"');\"><span class=\"qpad\">Save above text as answer.</span></a></div>";
        				Xishere = Xihtml;
        			} else if (a_href[i].innerHTML.match(regexp_js) && a_href[i].innerHTML != "javascript:void('');") {
        				tmp[i].innerHTML = tmp[i].innerHTML.replace(/(\<br\>){2}/gi,"<br> <br>");
        				var script_call = a_href[i].innerHTML.replace(/^javascript:/gi,"");
        				document.getElementById('Choices').innerHTML += "<a href=\"javascript:void('');\" class=\"qabutton\" onClick=\"answerQ('"+nextlabel+"');"+script_call+"\" "+a_target[i].innerHTML+"><span class=\"qpad\">"+tmp[i].innerHTML+"</span></a>";							
        			} else {
        				tmp[i].innerHTML = tmp[i].innerHTML.replace(/(\<br\>){2}/gi,"<br> <br>");
        				document.getElementById('Choices').innerHTML += "<a href=\""+a_href[i].innerHTML+"\" class=\"qabutton\" onClick=\"answerQ('"+nextlabel+"');\" "+a_target[i].innerHTML+"><span class=\"qpad\">"+tmp[i].innerHTML+"</span></a>";				
        			}
        		}			
        
        		if (restar == undefined) {
        			document.getElementById('Choices').innerHTML += "<a href=\"javascript:void('');\" class=\"qabutton\" onClick=\"startAT('1');\"><span class=\"qpad\">Start over.</span></a>";
        		}
        				
        		if (QNum != 0) { 
        			scroll2Q(Jht);           	
        		} else if (restar != undefined) {
        			window.scrollTo(0,0);
        		}
        		if (Xishere != 0 && window.self == window.top) {
        			console.log("Set focus for: "+Xishere);
        			document.getElementById(Xishere).focus();
        		}
        		console.log("Q#: "+QNum);
        		QNum++;
        			
        	}
        
        	
        	function swapGOTO(QH,JH) {
        		var regex = new RegExp("GOTO:(\d*)(\.\d+)*");
        		if (regex.test(document.getElementById(QH).innerHTML)) {
        			var Qtext = document.getElementById(QH).innerHTML.match(/(GOTO:(\d*)(.\s*\d+)*)/);
        			document.getElementById('QandA').innerHTML += "<div id="+JH+" style=\"float:left;width:100%;height:1px;\">&nbsp;</div>";
        			// Add question
        			// note I added () around the < to avoid a < followed by a ? which causes problems in php
        			var Qtexttrans = document.getElementById(QH).innerHTML.replace(/(<)?GOTO:(\d*)(.\s*\d+)*>?/,"");
        			Qtexttrans = Qtexttrans.replace(/\s*$/,"");
        			if (Qtexttrans != "") {
        				document.getElementById('transcript').value += "BOT: "+Qtexttrans+"\n";
        			}
        			if (document.getElementById(QH).innerHTML.match(/^GOTO:(\d*)(.\s*\d+)*/)) {
        				document.getElementById('QandA').innerHTML += document.getElementById(QH).innerHTML.replace(/(<)?GOTO:(\d*)(.\s*\d+)*>?/,"<"+Qtext+">");
        			} else {
        				document.getElementById('QandA').innerHTML += "<div class='frame'><div class='full'><div class='question_text'>"+ document.getElementById(QH).innerHTML.replace(/(<)?GOTO:(\d*)(.\s*\d+)*>?/,"<"+Qtext+">")+"</div></div><div class='question_arrow'></div></div>";						
        			}
        			// replace GOTO with text
        			label = Qtext[0].replace("GOTO:","");
        			Qhtml = 'Q-'+label;
        			if (document.getElementById(Dhtml)) {
        				document.getElementById('doc').innerHTML += document.getElementById(Dhtml).innerHTML;
        			}
        			Dhtml = 'D-'+label;
        			GOTOfired = 1;
        			swapGOTO(Qhtml,JH);
        		}
        	}
        
        	
        	function scroll2Q(id) {
        		var top = document.getElementById(id).offsetTop; //Getting Y of target element
        		console.log("Jump to Y for ("+id+"): "+top);
        		//adapted from https://github.com/Yappli/smooth-scroll
        		var speed = 800;
        		var moving_frequency = 5; // Affects performance !
        		var hop_count = speed/moving_frequency
                var getScrollTopDocumentAtBegin = document.documentElement.scrollTop + document.body.scrollTop;
                var gap = (top - getScrollTopDocumentAtBegin) / hop_count;
        		for(var i = 1; i <= hop_count; i++)
                {
                	(function()
                   	{
                   		var hop_top_position = gap*i;
                   	    setTimeout(function(){  window.scrollTo(0, hop_top_position + getScrollTopDocumentAtBegin); }, moving_frequency*i);
                   	 })();
                }
        	}
        
        	function getElementsByIdIs(selectorTag, name) {
        		var items = [];
        		var myPosts = document.getElementsByTagName(selectorTag);
        			//omitting undefined null check for brevity
        			if (myPosts[0].id == name) {
        				items.push(myPosts[0]);
        			}
        		
        		return items;
        	}
        
        	function getElementsByIdRegExp(selectorTag, expression) {
        		// note you need to escape \ in the expression with \, i.e., \\ = \
        		var regex = new RegExp(expression);
        		var items = [];
        		var myPosts = document.getElementsByTagName(selectorTag);
        		for (var i = 0; i < myPosts.length; i++) {
        			if (regex.test(myPosts[i].id)) {
        				items.push(myPosts[i]);
        			}
        		}
        		
        		return items;
        	}	
        
        	// startAT QnA
        	function startAT(id) {
        		document.getElementById('ondeck').innerHTML = document.getElementById('original').value;
        		document.getElementById('QandA').innerHTML = "";
        		document.getElementById('transcript').value = "";
        		QNum = 0;
        		answerQ(id,'1');
        	}
        		
        	//show funtion
        	function show(id) { 
           		if (document.getElementById) { // DOM3 = IE5, NS6
                	document.getElementById(id).style.display = 'block';
            	} else { 
                	if (document.layers) {  
                    	document.id.display = 'block';
                	} else {
                        document.all.id.style.display = 'block';
                	}
            	}
        	}
        
        	//hide funtion
        	function hide(id) { 
            	if (document.getElementById) { // DOM3 = IE5, NS6
                	document.getElementById(id).style.display = 'none';         
            	} else { 
                	if (document.layers) {  
                        document.id.display = 'none';
                	} else {
                        document.all.id.style.display = 'none';
                	}
            	}
        	}
        
        	//show OR hide funtion depends on if element is shown or hidden
        	function shoh(id) { 
            	if (document.getElementById) { // DOM3 = IE5, NS6
                	if (document.getElementById(id).style.display == "none"){
                    	document.getElementById(id).style.display = 'block';
                	} else {
                    	document.getElementById(id).style.display = 'none';         
                	}   
            	} else { 
                	if (document.layers) {  
                    	if (document.id.display == "none"){
                        	document.id.display = 'block';
                    	} else {
                        	document.id.display = 'none';
                    	}
                	} else {
                    	if (document.all.id.style.visibility == "none"){
                        	document.all.id.style.display = 'block';
                    	} else {
                        	document.all.id.style.display = 'none';
                    	}
                	}
            	}
        	}
        
        	function transcript(output) {
        		if (output == 1) {
        			return document.getElementById('transcript').value;
        		} else {
        			var output = document.getElementById('transcript').value.replace(/<[^>]*>/g,"");
        			return output;
        		}
        	}		
        	
        	function doc() {
        		return document.getElementById('doc').innerHTML;
        	}	
        
        	function mail2(to,subject,body) {
        		to = encodeURIComponent(to);
        		subject = encodeURIComponent(subject);
        		body = encodeURIComponent(body);
        		window.location.href = "mailto:"+to+"?subject="+subject+"&body="+body;
        	}
        	
        	function submit2(action,method,docAs,instructions,transcriptAs) {
        		document.FORM.action = action;
        		document.FORM.method = method; 
        		if (docAs) {
        			var doctext = document.createElement("textarea");
        			doctext.style.display ='none';
        			doctext.name= docAs;
        			doctext.value= document.getElementById('doc').innerHTML;
        			document.getElementById('FORM').appendChild(doctext);
        			if (instructions) {
        				var instructtext = document.createElement("textarea");
        				instructtext.type='hidden';
        				instructtext.style.display ='none';
        				instructtext.name= 'i';
        				instructtext.value= instructions;
        				document.getElementById('FORM').appendChild(instructtext);	
        			}
        		}
        		if (transcriptAs) {
        			var ttext = document.createElement("textarea");
        			ttext.type='hidden';
        			ttext.style.display ='none';
        			ttext.name= transcriptAs;
        			ttext.value= document.getElementById('transcript').value;
        			document.getElementById('FORM').appendChild(ttext);
        		}
        		document.getElementById('ondeck').innerHTML = "";
        		document.FORM.submit();
        	}
        
        	// h/t http://runnable.com/U5HC9xtufQpsu5aj/use-javascript-to-save-textarea-as-a-txt-file
        	function save2(filename,content)
        	{
        
        	// I'm using file system support as a proxy for support for this feature. 
        	// Check based on one found at: http://blog.teamtreehouse.com/building-an-html5-text-editor-with-the-filesystem-apis
        	// Handle vendor prefixes.
        	window.requestFileSystem = window.requestFileSystem || 
        							   window.webkitRequestFileSystem;
        	// Check for support.
        	if (window.requestFileSystem) {
        	// content = ID of textarea to save
        	// name = name to save file as, including file extension     
        	// grab the content of the form field and place it into a variable
        	//    var textToWrite = document.getElementById(content).value;
        	//  create a new Blob (html5 magic) that conatins the data from your form feild
        		var textFileAsBlob = new Blob([content], {type:'text/plain'});
        		
        	// Specify the name of the file to be saved
        		var fileNamecontentAs = filename;
        		
        	// Optionally allow the user to choose a file name by providing 
        	// an imput field in the HTML and using the collected data here
        	// var fileNamecontentAs = txtFileName.text;
        
        	// create a link for our script to 'click'
        		var downloadLink = document.createElement("a");
        	//  supply the name of the file (from the var above).
        	// you could create the name here but using a var
        	// allows more flexability later.
        		downloadLink.download = fileNamecontentAs;
        	// provide text for the link. This will be hidden so you
        	// can actually use anything you want.
        		downloadLink.innerHTML = "My Hidden Link";
        		
        	// allow our code to work in webkit & Gecko based browsers
        	// without the need for a if / else block.
        		window.URL = window.URL || window.webkitURL;
        			  
        	// Create the link Object.
        		downloadLink.href = window.URL.createObjectURL(textFileAsBlob);
        	// when link is clicked call a function to remove it from
        	// the DOM in case user wants to save a second file.
        		downloadLink.onclick = destroyClickedElement;
        	// make sure the link is hidden.
        		downloadLink.style.display = "none";
        	// add the link to the DOM
        		document.body.appendChild(downloadLink);
        		
        	// click the new link
        		downloadLink.click();
        	} else {
        		alert('This feature is not supported by your browser.');
        	}
        		
        	}
        
        	function destroyClickedElement(event)
        	{
        	// remove the link from the DOM
        		document.body.removeChild(event.target);
        	}
        
        	// EOF
      </script>
      <p></p>
      </div>
      </div>
      <div class="row">
        <div class="col-md-12">
          <p></p>
          <p></p>
        </div>
      </div>
      </div>
      <div class="section"></div>
  </body>

</html>
/*!
 * Default theme for Pingendo 
 * Homepage: http://pingendo.com  
 * Copyright 2015 Pingendo 
 * Licensed under MIT 
 * Based on Bootstrap v3.3.4
*/


/* Add custom CSS classes here 
 * 
 * img {
 *   box-shadow : 0px 0px 10px black !important;
 * }
*/

//
// Variables
// --------------------------------------------------
//== Colors
//
//## Gray and brand colors for use across Bootstrap.
@gray-base : #000;
@gray-darker : lighten(@gray-base, 13.5%); // #222
@gray-dark : lighten(@gray-base, 20%); // #333
@gray : lighten(@gray-base, 33.5%); // #555
@gray-light : lighten(@gray-base, 46.7%); // #777
@gray-lighter : lighten(@gray-base, 93.5%); // #eee
@brand-primary : #000626;
@brand-success : #5cb85c;
@brand-info : #1A3959;
@brand-warning : #f0ad4e;
@brand-danger : #d9534f;
//== Scaffolding
//
//## Settings for some of the most global styles.
//** Background color for `<body>`.
@body-bg : #001f3f;
//** Global text color on `<body>`.
@text-color : white;
//** Global textual link color.
@link-color : @brand-primary;
//** Link hover color set via `darken()` function.
@link-hover-color : darken(@link-color, 15%);
//** Link hover decoration.
@link-hover-decoration : underline;
//== Typography
//
//## Font, line-height, and color for body text, headings, and more.
@font-family-sans-serif : "Helvetica Neue",
Helvetica,
Arial,
sans-serif;
@font-family-serif : Georgia,
"Times New Roman",
Times,
serif;
//** Default monospace fonts for `<code>`, `<kbd>`, and `<pre>`.
@font-family-monospace : Menlo,
Monaco,
Consolas,
"Courier New",
monospace;
@font-family-base : Ubuntu;
@font-size-base : 24px;
@font-size-large : ceil((@font-size-base * 1.25)); // ~18px
@font-size-small : ceil((@font-size-base * 0.85)); // ~12px
@font-size-h1 : floor((@font-size-base * 2.6)); // ~36px
@font-size-h2 : floor((@font-size-base * 2.15)); // ~30px
@font-size-h3 : ceil((@font-size-base * 1.7)); // ~24px
@font-size-h4 : ceil((@font-size-base * 1.25)); // ~18px
@font-size-h5 : @font-size-base;
@font-size-h6 : ceil((@font-size-base * 0.85)); // ~12px
//** Unit-less `line-height` for use in components like buttons.
@line-height-base : 1.428571429; // 20/14
//** Computed "line-height" (`font-size` * `line-height`) for use with `margin`, `padding`, etc.
@line-height-computed : floor((@font-size-base * @line-height-base)); // ~20px
//** By default, this inherits from the `<body>`.
@headings-font-family : Libre Baskerville;
@headings-font-weight : 500;
@headings-line-height : 1.1;
@headings-color : inherit;
//== Iconography
//
//## Specify custom location and filename of the included Glyphicons icon font. Useful for those including Bootstrap via Bower.
//** Load fonts from this directory.
@icon-font-path : "../fonts/";
//** File name for all font files.
@icon-font-name : "glyphicons-halflings-regular";
//** Element ID within SVG icon file.
@icon-font-svg-id : "glyphicons_halflingsregular";
//== Components
//
//## Define common padding and border radius sizes and more. Values based on 14px text and 1.428 line-height (~20px to start).
@padding-base-vertical : 6px;
@padding-base-horizontal : 12px;
@padding-large-vertical : 10px;
@padding-large-horizontal : 16px;
@padding-small-vertical : 5px;
@padding-small-horizontal : 10px;
@padding-xs-vertical : 1px;
@padding-xs-horizontal : 5px;
@line-height-large : 1.3333333; // extra decimals for Win 8.1 Chrome
@line-height-small : 1.5;
@border-radius-base : 4px;
@border-radius-large : 6px;
@border-radius-small : 3px;
//** Global color for active items (e.g., navs or dropdowns).
@component-active-color : contrast(@component-active-bg, @text-color, @text-inverse, 43%);
//** Global background color for active items (e.g., navs or dropdowns).
@component-active-bg : @brand-primary;
//** Width of the `border` for generating carets that indicator dropdowns.
@caret-width-base : 4px;
//** Carets increase slightly in size for larger components.
@caret-width-large : 5px;
//== Tables
//
//## Customizes the `.table` component with basic values, each used across all table variations.
//** Padding for `<th>`s and `<td>`s.
@table-cell-padding : 8px;
//** Padding for cells in `.table-condensed`.
@table-condensed-cell-padding : 5px;
//** Default background color used for all tables.
@table-bg : transparent;
//** Background color used for `.table-striped`.
@table-bg-accent : #f9f9f9;
//** Background color used for `.table-hover`.
@table-bg-hover : #f5f5f5;
@table-bg-active : @table-bg-hover;
//** Border color for table and cell borders.
@table-border-color : #ddd;
//== Buttons
//
//## For each of Bootstrap's buttons, define text, background and border color.
@btn-font-weight : normal;
@btn-default-color : @text-color;
@btn-default-bg : @body-bg;
@btn-default-border : #ccc;
@btn-primary-color : white;
@btn-primary-bg : @brand-primary;
@btn-primary-border : darken(@btn-primary-bg, 5%);
@btn-success-color : white;
@btn-success-bg : @brand-success;
@btn-success-border : darken(@btn-success-bg, 5%);
@btn-info-color : white;
@btn-info-bg : @brand-info;
@btn-info-border : darken(@btn-info-bg, 5%);
@btn-warning-color : white;
@btn-warning-bg : @brand-warning;
@btn-warning-border : darken(@btn-warning-bg, 5%);
@btn-danger-color : contrast(@btn-danger-bg, @text-color, @text-inverse, 43%);
@btn-danger-bg : @brand-danger;
@btn-danger-border : darken(@btn-danger-bg, 5%);
@btn-link-disabled-color : @gray-light;
//== Forms
//
//##
//** `<input>` background color
@input-bg : #fff;
//** `<input disabled>` background color
@input-bg-disabled : @gray-lighter;
//** Text color for `<input>`s
@input-color : @gray;
//** `<input>` border color
@input-border : #ccc;
// TODO: Rename `@input-border-radius` to `@input-border-radius-base` in v4
//** Default `.form-control` border radius
@input-border-radius : @border-radius-base;
//** Large `.form-control` border radius
@input-border-radius-large : @border-radius-large;
//** Small `.form-control` border radius
@input-border-radius-small : @border-radius-small;
//** Border color for inputs on focus
@input-border-focus : #66afe9;
//** Placeholder text color
@input-color-placeholder : #999;
//** Default `.form-control` height
@input-height-base : (@line-height-computed + (@padding-base-vertical * 2) + 2);
//** Large `.form-control` height
@input-height-large : (ceil(@font-size-large * @line-height-large) + (@padding-large-vertical * 2) + 2);
//** Small `.form-control` height
@input-height-small : (floor(@font-size-small * @line-height-small) + (@padding-small-vertical * 2) + 2);
//** `.form-group` margin
@form-group-margin-bottom : 15px;
@legend-color : @gray-dark;
@legend-border-color : #e5e5e5;
//** Background color for textual input addons
@input-group-addon-bg : @gray-lighter;
//** Border color for textual input addons
@input-group-addon-border-color : @input-border;
//** Disabled cursor for form controls and buttons.
@cursor-disabled : not-allowed;
//== Dropdowns
//
//## Dropdown menu container and contents.
//** Background for the dropdown menu.
@dropdown-bg : #fff;
//** Dropdown menu `border-color`.
@dropdown-border : rgba(0, 0, 0, .15);
//** Dropdown menu `border-color` **for IE8**.
@dropdown-fallback-border : #ccc;
//** Divider color for between dropdown items.
@dropdown-divider-bg : #e5e5e5;
//** Dropdown link text color.
@dropdown-link-color : @gray-dark;
//** Hover color for dropdown links.
@dropdown-link-hover-color : darken(@gray-dark, 5%);
//** Hover background for dropdown links.
@dropdown-link-hover-bg : #f5f5f5;
//** Active dropdown menu item text color.
@dropdown-link-active-color : @component-active-color;
//** Active dropdown menu item background color.
@dropdown-link-active-bg : @component-active-bg;
//** Disabled dropdown menu item background color.
@dropdown-link-disabled-color : @gray-light;
//** Text color for headers within dropdown menus.
@dropdown-header-color : @gray-light;
//** Deprecated `@dropdown-caret-color` as of v3.1.0
@dropdown-caret-color : #000;
//-- Z-index master list
//
// Warning: Avoid customizing these values. They're used for a bird's eye view
// of components dependent on the z-axis and are designed to all work together.
//
// Note: These variables are not generated into the Customizer.
@zindex-navbar : 1000;
@zindex-dropdown : 1000;
@zindex-popover : 1060;
@zindex-tooltip : 1070;
@zindex-navbar-fixed : 1030;
@zindex-modal-background : 1040;
@zindex-modal : 1050;
//== Media queries breakpoints
//
//## Define the breakpoints at which your layout will change, adapting to different screen sizes.
// Extra small screen / phone
//** Deprecated `@screen-xs` as of v3.0.1
@screen-xs : 480px;
//** Deprecated `@screen-xs-min` as of v3.2.0
@screen-xs-min : @screen-xs;
//** Deprecated `@screen-phone` as of v3.0.1
@screen-phone : @screen-xs-min;
// Small screen / tablet
//** Deprecated `@screen-sm` as of v3.0.1
@screen-sm : 768px;
@screen-sm-min : @screen-sm;
//** Deprecated `@screen-tablet` as of v3.0.1
@screen-tablet : @screen-sm-min;
// Medium screen / desktop
//** Deprecated `@screen-md` as of v3.0.1
@screen-md : 992px;
@screen-md-min : @screen-md;
//** Deprecated `@screen-desktop` as of v3.0.1
@screen-desktop : @screen-md-min;
// Large screen / wide desktop
//** Deprecated `@screen-lg` as of v3.0.1
@screen-lg : 1200px;
@screen-lg-min : @screen-lg;
//** Deprecated `@screen-lg-desktop` as of v3.0.1
@screen-lg-desktop : @screen-lg-min;
// So media queries don't overlap when required, provide a maximum
@screen-xs-max : (@screen-sm-min - 1);
@screen-sm-max : (@screen-md-min - 1);
@screen-md-max : (@screen-lg-min - 1);
//== Grid system
//
//## Define your custom responsive grid.
//** Number of columns in the grid.
@grid-columns : 12;
//** Padding between columns. Gets divided in half for the left and right.
@grid-gutter-width : 30px;
// Navbar collapse
//** Point at which the navbar becomes uncollapsed.
@grid-float-breakpoint : @screen-sm-min;
//** Point at which the navbar begins collapsing.
@grid-float-breakpoint-max : (@grid-float-breakpoint - 1);
//== Container sizes
//
//## Define the maximum width of `.container` for different screen sizes.
// Small screen / tablet
@container-tablet : (720px + @grid-gutter-width);
//** For `@screen-sm-min` and up.
@container-sm : @container-tablet;
// Medium screen / desktop
@container-desktop : (940px + @grid-gutter-width);
//** For `@screen-md-min` and up.
@container-md : @container-desktop;
// Large screen / wide desktop
@container-large-desktop : (1140px + @grid-gutter-width);
//** For `@screen-lg-min` and up.
@container-lg : @container-large-desktop;
//== Navbar
//
//##
// Basics of a navbar
@navbar-height : 50px;
@navbar-margin-bottom : @line-height-computed;
@navbar-border-radius : @border-radius-base;
@navbar-padding-horizontal : floor((@grid-gutter-width / 2));
@navbar-padding-vertical : ((@navbar-height - @line-height-computed) / 2);
@navbar-collapse-max-height : 340px;
@navbar-default-color : white;
@navbar-default-bg : #001f3f;
@navbar-default-border : darken(@navbar-default-bg, 6.5%);
// Navbar links
@navbar-default-link-color : @navbar-default-color;
@navbar-default-link-hover-color : @navbar-default-color;
@navbar-default-link-hover-bg : transparent;
@navbar-default-link-active-color : @navbar-default-color;
@navbar-default-link-active-bg : darken(@navbar-default-bg, 6.5%);
@navbar-default-link-disabled-color : #ccc;
@navbar-default-link-disabled-bg : transparent;
// Navbar brand label
@navbar-default-brand-color : @navbar-default-link-color;
@navbar-default-brand-hover-color : darken(@navbar-default-brand-color, 10%);
@navbar-default-brand-hover-bg : transparent;
// Navbar toggle
@navbar-default-toggle-hover-bg : #ddd;
@navbar-default-toggle-icon-bar-bg : #888;
@navbar-default-toggle-border-color : #ddd;
// Inverted navbar
// Reset inverted navbar basics
@navbar-inverse-color : lighten(@gray-light, 15%);
@navbar-inverse-bg : #222;
@navbar-inverse-border : darken(@navbar-inverse-bg, 10%);
// Inverted navbar links
@navbar-inverse-link-color : lighten(@gray-light, 15%);
@navbar-inverse-link-hover-color : #fff;
@navbar-inverse-link-hover-bg : transparent;
@navbar-inverse-link-active-color : @navbar-inverse-link-hover-color;
@navbar-inverse-link-active-bg : darken(@navbar-inverse-bg, 10%);
@navbar-inverse-link-disabled-color : #444;
@navbar-inverse-link-disabled-bg : transparent;
// Inverted navbar brand label
@navbar-inverse-brand-color : @navbar-inverse-link-color;
@navbar-inverse-brand-hover-color : #fff;
@navbar-inverse-brand-hover-bg : transparent;
// Inverted navbar toggle
@navbar-inverse-toggle-hover-bg : #333;
@navbar-inverse-toggle-icon-bar-bg : #fff;
@navbar-inverse-toggle-border-color : #333;
//== Navs
//
//##
//=== Shared nav styles
@nav-link-padding : 10px 15px;
@nav-link-hover-bg : @gray-lighter;
@nav-disabled-link-color : @gray-light;
@nav-disabled-link-hover-color : @gray-light;
//== Tabs
@nav-tabs-border-color : #ddd;
@nav-tabs-link-hover-border-color : @gray-lighter;
@nav-tabs-active-link-hover-bg : @body-bg;
@nav-tabs-active-link-hover-color : @gray;
@nav-tabs-active-link-hover-border-color : #ddd;
@nav-tabs-justified-link-border-color : #ddd;
@nav-tabs-justified-active-link-border-color : @body-bg;
//== Pills
@nav-pills-border-radius : @border-radius-base;
@nav-pills-active-link-hover-bg : @component-active-bg;
@nav-pills-active-link-hover-color : @component-active-color;
//== Pagination
//
//##
@pagination-color : @link-color;
@pagination-bg : #fff;
@pagination-border : #ddd;
@pagination-hover-color : @link-hover-color;
@pagination-hover-bg : @gray-lighter;
@pagination-hover-border : #ddd;
@pagination-active-color : #fff;
@pagination-active-bg : @brand-primary;
@pagination-active-border : @brand-primary;
@pagination-disabled-color : @gray-light;
@pagination-disabled-bg : #fff;
@pagination-disabled-border : #ddd;
//== Pager
//
//##
@pager-bg : @pagination-bg;
@pager-border : @pagination-border;
@pager-border-radius : 15px;
@pager-hover-bg : @pagination-hover-bg;
@pager-active-bg : @pagination-active-bg;
@pager-active-color : @pagination-active-color;
@pager-disabled-color : @pagination-disabled-color;
//== Jumbotron
//
//##
@jumbotron-padding : 30px;
@jumbotron-color : inherit;
@jumbotron-bg : @gray-lighter;
@jumbotron-heading-color : inherit;
@jumbotron-font-size : ceil((@font-size-base * 1.5));
@jumbotron-heading-font-size : ceil((@font-size-base * 4.5));
//== Form states and alerts
//
//## Define colors for form feedback states and, by default, alerts.
@state-success-text : @brand-success;
@state-success-bg : lighten(@brand-success, 20%);
@state-success-border : darken(spin(@state-success-bg, -10), 5%);
@state-info-text : @brand-info;
@state-info-bg : lighten(@brand-info, 20%);
@state-info-border : darken(spin(@state-info-bg, -10), 7%);
@state-warning-text : @brand-warning;
@state-warning-bg : lighten(@brand-warning, 20%);
@state-warning-border : darken(spin(@state-warning-bg, -10), 5%);
@state-danger-text : @brand-danger;
@state-danger-bg : lighten(@brand-danger, 20%);
@state-danger-border : darken(spin(@state-danger-bg, -10), 5%);
//== Tooltips
//
//##
//** Tooltip max width
@tooltip-max-width : 200px;
//** Tooltip text color
@tooltip-color : #fff;
//** Tooltip background color
@tooltip-bg : #000;
@tooltip-opacity : .9;
//** Tooltip arrow width
@tooltip-arrow-width : 5px;
//** Tooltip arrow color
@tooltip-arrow-color : @tooltip-bg;
//== Popovers
//
//##
//** Popover body background color
@popover-bg : #fff;
//** Popover maximum width
@popover-max-width : 276px;
//** Popover border color
@popover-border-color : rgba(0, 0, 0, .2);
//** Popover fallback border color
@popover-fallback-border-color : #ccc;
//** Popover title background color
@popover-title-bg : darken(@popover-bg, 3%);
//** Popover arrow width
@popover-arrow-width : 10px;
//** Popover arrow color
@popover-arrow-color : @popover-bg;
//** Popover outer arrow width
@popover-arrow-outer-width : (@popover-arrow-width + 1);
//** Popover outer arrow color
@popover-arrow-outer-color : fadein(@popover-border-color, 5%);
//** Popover outer arrow fallback color
@popover-arrow-outer-fallback-color : darken(@popover-fallback-border-color, 20%);
//== Labels
//
//##
//** Default label background color
@label-default-bg : @gray-light;
//** Primary label background color
@label-primary-bg : @brand-primary;
//** Success label background color
@label-success-bg : @brand-success;
//** Info label background color
@label-info-bg : @brand-info;
//** Warning label background color
@label-warning-bg : @brand-warning;
//** Danger label background color
@label-danger-bg : @brand-danger;
//** Default label text color
@label-color : #fff;
//** Default text color of a linked label
@label-link-hover-color : #fff;
//== Modals
//
//##
//** Padding applied to the modal body
@modal-inner-padding : 15px;
//** Padding applied to the modal title
@modal-title-padding : 15px;
//** Modal title line-height
@modal-title-line-height : @line-height-base;
//** Background color of modal content area
@modal-content-bg : #fff;
//** Modal content border color
@modal-content-border-color : rgba(0, 0, 0, .2);
//** Modal content border color **for IE8**
@modal-content-fallback-border-color : #999;
//** Modal backdrop background color
@modal-backdrop-bg : #000;
//** Modal backdrop opacity
@modal-backdrop-opacity : .5;
//** Modal header border color
@modal-header-border-color : #e5e5e5;
//** Modal footer border color
@modal-footer-border-color : @modal-header-border-color;
@modal-lg : 900px;
@modal-md : 600px;
@modal-sm : 300px;
//== Alerts
//
//## Define alert colors, border radius, and padding.
@alert-padding : 15px;
@alert-border-radius : @border-radius-base;
@alert-link-font-weight : bold;
@alert-success-bg : @state-success-bg;
@alert-success-text : @state-success-text;
@alert-success-border : @state-success-border;
@alert-info-bg : @state-info-bg;
@alert-info-text : @state-info-text;
@alert-info-border : @state-info-border;
@alert-warning-bg : @state-warning-bg;
@alert-warning-text : @state-warning-text;
@alert-warning-border : @state-warning-border;
@alert-danger-bg : @state-danger-bg;
@alert-danger-text : @state-danger-text;
@alert-danger-border : @state-danger-border;
//== Progress bars
//
//##
//** Background color of the whole progress component
@progress-bg : #f5f5f5;
//** Progress bar text color
@progress-bar-color : #fff;
//** Variable for setting rounded corners on progress bar.
@progress-border-radius : @border-radius-base;
//** Default progress bar color
@progress-bar-bg : @brand-primary;
//** Success progress bar color
@progress-bar-success-bg : @brand-success;
//** Warning progress bar color
@progress-bar-warning-bg : @brand-warning;
//** Danger progress bar color
@progress-bar-danger-bg : @brand-danger;
//** Info progress bar color
@progress-bar-info-bg : @brand-info;
//== List group
//
//##
//** Background color on `.list-group-item`
@list-group-bg : @body-bg;
//** `.list-group-item` border color
@list-group-border : darken(@list-group-bg, 40%);
//** List group border radius
@list-group-border-radius : @border-radius-base;
//** Background color of single list items on hover
@list-group-hover-bg : #f5f5f5;
//** Text color of active list items
@list-group-active-color : @component-active-color;
//** Background color of active list items
@list-group-active-bg : @component-active-bg;
//** Border color of active list elements
@list-group-active-border : @list-group-active-bg;
//** Text color for content within active list items
@list-group-active-text-color : darken(@list-group-active-bg, 40%);
//** Text color of disabled list items
@list-group-disabled-color : @gray-light;
//** Background color of disabled list items
@list-group-disabled-bg : @gray-lighter;
//** Text color for content within disabled list items
@list-group-disabled-text-color : @list-group-disabled-color;
@list-group-link-color : #555;
@list-group-link-hover-color : @list-group-link-color;
@list-group-link-heading-color : #333;
//== Panels
//
//##
@panel-bg : @body-bg;
@panel-body-padding : 15px;
@panel-heading-padding : 10px 15px;
@panel-footer-padding : @panel-heading-padding;
@panel-border-radius : @border-radius-base;
//** Border color for elements within panels
@panel-inner-border : #ddd;
@panel-footer-bg : #f5f5f5;
@panel-default-text : @gray-dark;
@panel-default-border : #ddd;
@panel-default-heading-bg : #f5f5f5;
@panel-primary-text : contrast(@brand-primary, @text-color, @text-inverse, 43%);
@panel-primary-border : @brand-primary;
@panel-primary-heading-bg : @brand-primary;
@panel-success-text : @state-success-text;
@panel-success-border : @state-success-border;
@panel-success-heading-bg : @state-success-bg;
@panel-info-text : @state-info-text;
@panel-info-border : @state-info-border;
@panel-info-heading-bg : @state-info-bg;
@panel-warning-text : @state-warning-text;
@panel-warning-border : @state-warning-border;
@panel-warning-heading-bg : @state-warning-bg;
@panel-danger-text : @state-danger-text;
@panel-danger-border : @state-danger-border;
@panel-danger-heading-bg : @state-danger-bg;
//== Thumbnails
//
//##
//** Padding around the thumbnail image
@thumbnail-padding : 4px;
//** Thumbnail background color
@thumbnail-bg : @body-bg;
//** Thumbnail border color
@thumbnail-border : #ddd;
//** Thumbnail border radius
@thumbnail-border-radius : @border-radius-base;
//** Custom text color for thumbnail captions
@thumbnail-caption-color : @text-color;
//** Padding around the thumbnail caption
@thumbnail-caption-padding : 9px;
//== Wells
//
//##
@well-bg : #f5f5f5;
@well-border : darken(@well-bg, 7%);
//== Badges
//
//##
@badge-color : #fff;
//** Linked badge text color on hover
@badge-link-hover-color : #fff;
@badge-bg : @gray-light;
//** Badge text color in active nav link
@badge-active-color : @link-color;
//** Badge background color in active nav link
@badge-active-bg : #fff;
@badge-font-weight : bold;
@badge-line-height : 1;
@badge-border-radius : 10px;
//== Breadcrumbs
//
//##
@breadcrumb-padding-vertical : 8px;
@breadcrumb-padding-horizontal : 15px;
//** Breadcrumb background color
@breadcrumb-bg : #f5f5f5;
//** Breadcrumb text color
@breadcrumb-color : #ccc;
//** Text color of current page in the breadcrumb
@breadcrumb-active-color : @gray-light;
//** Textual separator for between breadcrumb elements
@breadcrumb-separator : "/";
//== Carousel
//
//##
@carousel-text-shadow : 0 1px 2px rgba(0, 0, 0, .6);
@carousel-control-color : #fff;
@carousel-control-width : 15%;
@carousel-control-opacity : .5;
@carousel-control-font-size : 20px;
@carousel-indicator-active-bg : #fff;
@carousel-indicator-border-color : #fff;
@carousel-caption-color : #fff;
//== Close
//
//##
@close-font-weight : bold;
@close-color : #000;
@close-text-shadow : 0 1px 0 #fff;
//== Code
//
//##
@code-color : #c7254e;
@code-bg : #f9f2f4;
@kbd-color : #fff;
@kbd-bg : #333;
@pre-bg : #f5f5f5;
@pre-color : @gray-dark;
@pre-border-color : #ccc;
@pre-scrollable-max-height : 340px;
//== Type
//
//##
//** Horizontal offset for forms and lists.
@component-offset-horizontal : 180px;
//** Text muted color
@text-muted : @gray-light;
//** Abbreviations and acronyms border color
@abbr-border-color : @gray-light;
//** Headings small color
@headings-small-color : @gray-light;
//** Blockquote small color
@blockquote-small-color : @gray-light;
//** Blockquote font size
@blockquote-font-size : (@font-size-base * 1.25);
//** Blockquote border color
@blockquote-border-color : @gray-lighter;
//** Page header border color
@page-header-border-color : @gray-lighter;
//** Width of horizontal description list titles
@dl-horizontal-offset : @component-offset-horizontal;
//** Horizontal line color.
@hr-border : @gray-lighter;
// Pingendo variables
@section-spacing : 35px;
// Core variables and mixins
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/mixins.less";
// Reset and dependencies
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/normalize.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/print.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/glyphicons.less";
// Core CSS
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/scaffolding.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/type.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/code.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/grid.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/tables.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/forms.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/buttons.less";
// Components
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/component-animations.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/dropdowns.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/button-groups.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/input-groups.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/navs.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/navbar.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/breadcrumbs.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/pagination.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/pager.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/labels.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/badges.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/jumbotron.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/thumbnails.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/alerts.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/progress-bars.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/media.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/list-group.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/panels.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/responsive-embed.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/wells.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/close.less";
// Components w/ JavaScript
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/modals.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/tooltip.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/popovers.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/carousel.less";
// Utility classes
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/utilities.less";
@import "https://raw.githubusercontent.com/twbs/bootstrap/v3.3.4/less/responsive-utilities.less";
@import "https://raw.githubusercontent.com/Pingendo/pingendo-bootstrap/gh-pages/less/pingendo-custom.less";

/* PINGENDO COMMENT DO NOT REMOVE */
