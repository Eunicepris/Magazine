# Magazine



## post
titre = models.CharField()
description = models.TextField()
image = models.ImageField()
date_add= models.DateTmeField()
date_upd = models.DateTimeField()
statut = models.BooleanField()
categories_id = models.ForeignKey()



## Categories

titre = models.CharField()
description = models.TextField()
image = models.ImageField()
date_add= models.DateTmeField()
statut = models.BooleanField()
date_upd = models.DateTimeField()

## Comment

titre = models.CharField()
description = models.TextField()
date_add= models.DateTmeField()
date_upd = models.DateTimeField()
statut = models.BooleanField()
post_id = models.ForeignKey()

