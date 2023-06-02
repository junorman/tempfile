# 

Bonjour Madame, Monsieur,
Je suis Etudiant inscrit en Alternance niveau Master 1 Architect Informatique à l’école INSTA, actuellement j’occupe le poste de Concepteur Développeur d’applications au sein de l’entreprise Natixis, je viens respectueusement auprès vous solliciter votre aide suite à un souci qui j’ai actuellement qui m’empêche d’exercer certaines activités au sein de mon entreprise, suite à ma demande de renouvèlement de titre de séjour. 
La Direction des Ressources Humaines au sein de mon entreprise me demande une attestation ou un récépissé prouvant l’action de ma demande de renouvellement de mon titre de séjour auprès de vos instances administratives. Car je les ai présentés le document montrant le dépôt de ma demande faite 31 Mai 2023 mais celle-ci ne leurs convient pas. A cela je tenais à vous demander l’obtention d’un récépissé qui me permettra de reprendre avec mes activités au sein de l’entreprise et elle permettra aussi à la Direction des Ressources Humaines de mettre mes données personnelles à jours


https://stackoverflow.com/questions/23191832/how-do-i-update-specific-key-value-of-the-local-storage-array

https://www.section.io/engineering-education/how-to-use-localstorage-with-javascript/

localStorage.removeItem("mytime");

https://www.c-sharpcorner.com/UploadFile/65794e/remove-filtered-sessionstorage-and-localstorage/

charline.pasquier@natixis.com

https://www.youtube.com/watch?v=NxVCq4p0Kb0

Nom d'utilisateur : Olivier Junior.GUEMBY
oiMot de passe : yEGek$35#I8qE


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
