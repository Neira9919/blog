---
layout: page
title: Contacto
permalink: /contact
comments: false
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Envía tu correo a {{site.name}}. Responderé tan pronto como pueda!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nombre*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Mensaje*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Enviar">
</form>