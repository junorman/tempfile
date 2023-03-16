# 
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
