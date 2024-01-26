# 

https://www.youtube.com/watch?v=dDsitOmZq3U
https://www.youtube.com/watch?v=-iQG94zv6Aw
https://www.youtube.com/watch?v=GzlQS-0eWEI
https://www.youtube.com/watch?v=_NDBbiVINlA

https://www.youtube.com/watch?v=dLXSJdTK9QI
https://www.youtube.com/watch?v=1KZ-tJRLU5I
https://www.youtube.com/watch?v=3l_CpD-IaJE

https://stackoverflow.com/questions/23191832/how-do-i-update-specific-key-value-of-the-local-storage-array

https://www.section.io/engineering-education/how-to-use-localstorage-with-javascript/

localStorage.removeItem("mytime");

https://www.c-sharpcorner.com/UploadFile/65794e/remove-filtered-sessionstorage-and-localstorage/

charline.pasquier@natixis.com

https://www.youtube.com/watch?v=NxVCq4p0Kb0

LinkedIn: https://www.linkedin.com/in/olivier-junior-guemby-9a9577172?trk=contact-info


Nom d'utilisateur : Olivier Junior.GUEMBY
oiMot de passe : yEGek$35#I8qE

https://www.youtube.com/watch?v=bRVTWzsu3-M
https://www.youtube.com/watch?v=Ik9jYUVT9do

https://www.youtube.com/watch?v=V0gMajxp990
https://www.youtube.com/watch?v=Cq8Hokn2SAQ

SQL
http://www.salihayacoub.com/420Kba/TransacSql.pdf
===================================
https://www.jqueryscript.net/table/Lightweight-Client-Side-Data-Grid-Plugin-with-jQuery-jsgrid.html

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
	<select class="" id="column">
		<option value="">choisir</option>
		<option id="1" data-v1="0" value="1">NoLB</option>
		<option id="2" data-v2="0" value="2">Description</option>
		<option id="3" data-v3="0" value="3">Libelle</option>
		<option id="4" data-v4="0" value="4">Fournisseur</option>
		<option id="5" data-v5="0" value="5">Chain</option>
		<option id="6" data-v6="0" value="6">Login</option>
		<option id="7" data-v7="0" value="7">Apllication</option>
		<option id="8" data-v8="0" value="8">Application Domain</option>
		<option id="9" data-v9="0" value="9">Application Scope</option>
		<option id="10" data-v10="0" value="10">Projet</option>
		<option id="11" data-v11="0" value="11">Budget</option>
		<option id="12" data-v12="0" value="12">Proforma</option>
		<option id="13" data-v13="0" value="13">Atterissage</option>
		<option id="14" data-v14="0" value="14">BR06</option>
		<option id="15" data-v15="0" value="15">BR09</option>
	</select>

	<button id="add">dbclick</button>

	<br><br>
	<table>
		<tr>
			<th>NoLB</th>
			<th>Description</th>
			<th class="view">Libelle</th>
		</tr>
		<tr>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</table>
<style type="text/css">
	
</style>
<script src="https://code.jquery.com/jquery-3.6.4.min.js" integrity="sha256-oP6HI9z1XaZNBrJURtCoUT5SUnxFr8s3BzRl+cbzUq8=" crossorigin="anonymous"></script>

<script type="text/javascript">
	$(document).ready(function(){
		var i = 0;
		
		//$('#add').dblclick(function(){ alert('');})
		$('.view').css('visibility', 'hidden');	

		$('#column').change(function (e){
			var v1 = $("#1").val();
			var v2 = $("#2").val();
			var v3 = $("#3").val();
	        
	            
            	if(e.target.value == v1 && $('#1').data('v1') == 0) {
            		if(i < 2){
            			$('#1').css('color', 'red');
		      			$('#1').data('v1', '1');
		      			i++;
            		}
		      	 return false;
			    }else if(e.target.value == v1 && $('#1').data('v1') == 1) {
			      $('#1').css('color', 'black');
			      $('#1').data('v1', '0');
			      i--;
			      return false;
			    }  else if(e.target.value == v2 && $('#2').data('v2') == 0) {
			    	if(i < 2){
			    		$('#2').css('color', 'green');
			      		$('#2').data('v2', '1');
			      		i++;
			    	}
			      return false;
			    } else if(e.target.value == v2 && $('#2').data('v2') == 1) {
			      $('#2').css('color', 'black');
			      $('#2').data('v2', '0');
			      i--;
			      return false;
			    }else if(e.target.value == v3 && $('#3').data('v3') == 0) {
			    	if(i < 2){
			    		$('#3').css('color', 'blue');
					    $('#3').data('v3', '1');
					    i++;
			    	}
			      return false;
			    }
			     else if(e.target.value == v3 && $('#3').data('v3') == 1) {
			      $('#3').css('color', 'black');
			      $('#3').data('v3', '0');
			      i--;
			      return false;
			    }
	            
	            
		
	    });

    });
</script>
</body>
</html>


<!-- <select onchange="changeColor();" class="color" id="rgb">
  <option id="red" value="Red">Red</option>
  <option id="green" value="Green">Green</option>
  <option id="blue" value="Blue">Blue</option>
</select>

<script type="text/javascript">
	function changeColor() {
    var red = document.getElementById('red');
    var green = document.getElementById('green');
    var blue = document.getElementById('blue');

    if(event.target.value == red) {
      red.style.color = "red";
    } else if(event.target.value == green) {
      green.style.color = "green";
    } else if(event.target.value == blue) {
      blue.style.color = "blue";
    } else  {
      alert("There was an error!");
      }
  };
</script> -->




===================================


:::::::::::::::::::::::::::::::::::::::::::::::
$('.btn-follow').click(function(e){
        e.preventDefault();
        var id_user_following=$(this).attr('id');
        var id_following=id_user_following.split("users")[1];
        var id_user_follower=$(this).data('session_id');
        var id_follower=id_user_follower.split("session")[1];
        var action=$(this).data('action');
        var image=$(this).data('image');
        var nom=$(this).data('nom');
        var prenom=$(this).data('prenom');
        
            $.ajax({
                type: "POST",
                url: "../users_traitements/follow.php",
                data: {id_follower:id_follower, id_following:id_following, action:action, 
                    image:image, nom:nom, prenom:prenom},
                success: function (data) {
                     
                     if ( action == 'unfollow') {
                         $('#users'+id_following).html("<i class='fa fa-check'></i> S'ABONNER").data('action', 'follow'); 
                          
                          $('.content').fadeIn().html(
                            '<div class="alert alert-block alert-default">'
                              +'<a href="#" class="close_alert" data-dsimmiss="alert" aria-label="close">&times;</a>'
                              +'<p><strong>Abonnement supprimé</strong></p>  '
                            +'</div>').css('color', 'blue');

                          setTimeout(function(){
                         $('.content').fadeOut('slow');
                       },10000);

                      $('.close_alert').click(function(e){
                            e.preventDefault();
                            $('.content').html('');
                         });

                     }else{
                         $('#users'+id_following).html("<i class='fa fa-trash'></i> SE DESABONNER").data('action', 'unfollow');

                         $('.content').fadeIn().html(
                            '<div class="alert alert-block alert-default">'
                              +'<a href="#" class="close_alert" data-dsimmiss="alert" aria-label="close">&times;</a>'
                              +"<p><strong>Abonnement ajouté</strong></p>  "
                              +'<p><< Vous reçevrez desormais les notifications de <strong>'+name_abonnement+'</strong> >> <i class="fa fa-bell"></i></p>  '
                            +'</div>').css('color', 'blue');

                          setTimeout(function(){
                         $('.content').fadeOut('slow');
                       },10000);
                         
                         $('.close_alert').click(function(e){
                            e.preventDefault();
                            $('.content').html('');
                         });
                         
                         
                     }
                  
                }
            });
          
    });
:::::::::::::::::::::::::::::::::::::::::::::::



-----------------------------------------------
<div class="user-ads-action">
                                                <?php if (isset($_SESSION['id'])) {
                                                      
                                                      if ($_SESSION['id'] == $user['id']) {
                                                ?>
                                               <!--  <a class="btn btn-sm  btn-success "><i class=" icon-plus"></i> Follow </a> -->
                                                <?php    
                                                  }
                                                  else{
                                                  ?>
                                                  <?php if ($rowcount_follows == 0) {
                                                    ?>
                                                       <a class="btn btn-sm  btn-success btn-follow" id="users<?php echo $user['id']; ?>" data-session_id="session<?php echo $_SESSION['id']; ?>" data-action="follow"
                                                        data-image="<?php echo $_SESSION['image']; ?>" 
                                                        data-nom="<?php echo $_SESSION['nom']; ?>" 
                                                        data-prenom="<?php echo $_SESSION['prenom']; ?>">
                                                    <i class="fa fa-check"></i> S'ABONNER 
                                                  </a>
                                                    <?php
                                                  }else{
                                                  ?>
                                                   <a class="btn btn-sm  btn-success btn-follow" id="users<?php echo $user['id']; ?>" data-session_id="session<?php echo $_SESSION['id']; ?>" data-action="unfollow"

                                                    data-image="<?php echo $_SESSION['image']; ?>" 
                                                        data-nom="<?php echo $_SESSION['nom']; ?>" 
                                                        data-prenom="<?php echo $_SESSION['prenom']; ?>">
                                                    <i class="fa fa-trash"></i> SE DESABONNER 
                                                  </a>
                                                  <?php
                                                  } ?>
                                                 
                                                <?php
                                                  }
                                                }else{
                                                ?>
                                                  <a class="btn btn-sm  btn-success " href="login.php">
                                                    <i class="fa fa-check"></i> S'ABONNER </a>
                                                  <?php
                                                } ?>
                                                
                                            </div>
-----------------------------------------------


<?php if ($row['user_etat'] == 0) {?>
            <button <?php echo deactivate_button($DESACTIVER, DESACTIVER) ?> class="btn btn-sm btn-warning btn-modes" 
            id="desactiver<?php echo $row['user_id'] ?>" 
            data-action="desactiver" data-etat="1">
                <i class="fa fa-unlock"></i> Desactiver
            </button>
            <?php }else{?>
            <button <?php echo deactivate_button($ACTIVER, ACTIVER) ?> class="btn btn-sm btn-warning btn-modes" 
            id="activer<?php echo $row['user_id'] ?>" 
            data-action="activer" data-etat="0">
                <i class="fa fa-lock"></i> Activiter
            </button>
            <?php } ?>
            
            
                 $('.btn-modes').click(function(e){
					e.preventDefault();
					var id = $(this).attr('id');
					var action = $(this).data('action');
					var etat = $(this).data('etat');
					var mode_id = id.split('activer')[1];

					$.ajax({  
			                url:"./traitements/modes_activation.php",  
			                method:"POST",  
			                data:{id:mode_id, etat:etat},  
			                cache:false,
			                success:function(res)  
			                {  
			                	if (action == "activer") {
			                		$('#'+id).html('<i class="fa fa-lock"> Desactiver').data('action', 'desactiver').data('etat', '1');
			                	}else{
			                		$('#'+id).html('<i class="fa fa-unlock"> Activer').data('action', 'activer').data('etat', '0');
			                	}
			                } 
		            });

				});


https://github.com/josecebe/twbs-pagination
https://stackoverflow.com/questions/29491429/how-to-write-a-join-with-not-equal-in-linq-to-sql


<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
<style type="text/css">
	.wrapper{
  margin: 60px auto;
  text-align: center;
}
h1{
  margin-bottom: 1.25em;
}
#pagination-demo{
  display: inline-block;
  margin-bottom: 1.75em;
}
#pagination-demo li{
  display: inline-block;
}

.page-content{
  background: #eee;
  display: inline-block;
  padding: 10px;
  width: 100%;
  max-width: 660px;
}
</style>
<div class="wrapper">
  <div class="container">
    
    <div class="row">
      <div class="col-sm-12">
        <h1>jQuery Pagination</h1>
        <p>Simple pagination using the TWBS pagination JS library. Click the buttons below to navigate to the appropriate content</p>
        <ul id="pagination-demo" class="pagination-sm"></ul>
      </div>
    </div>

    <div id="page-content" class="page-content">Page 1</div>
  </div>
</div>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/twbs-pagination/1.4.2/jquery.twbsPagination.min.js"></script>

  <script type="text/javascript">
  	$('#pagination-demo').twbsPagination({
        totalPages: 16,
        visiblePages: 6,
        next: 'Next',
        prev: 'Prev',
        onPageClick: function (event, page) {
            //fetch content and render here
            $('#page-content').text('Page ' + page) + ' content here';
        }
    });
  </script>
</body>
</html>
