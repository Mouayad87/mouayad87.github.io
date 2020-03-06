Menu fixe apres scroll----------------------
Url     : http://codes-sources.commentcamarche.net/source/101976-menu-fixe-apres-scrollAuteur  : @karamelDate    : 19/05/2017
Licence :
=========

Ce document intitul� � Menu fixe apres scroll � issu de CommentCaMarche
(codes-sources.commentcamarche.net) est mis � disposition sous les termes de
la licence Creative Commons. Vous pouvez copier, modifier des copies de cette
source, dans les conditions fix�es par la licence, tant que cette note
appara�t clairement.

Description :
=============

il s'agit du menu qui se fixe a un certain niveau de scroll contrairement a ce q
ue l'on voit d'habitude ici tout est géré par le javascript il n'y a pas de ch
angement de class et il est possible de mettre plusieurs element
<br />
<br />
la mise en place est des plus simple il suffit de mettre un attribut data-stic e
n spécifiant la marge du haut
<br />
<br /><pre class="code" data-mode="html"
>&lt;div id=&apos;autre&apos; data-stic=&quot;40&quot;&gt;&lt;/div&gt;</pre>
<b
r />
<br />et l'element doit avoir un position css en fixed
<br />
<br /><pre
 class="code" data-mode="js">position:fixed;</pre>
