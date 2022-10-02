
Before you start to [calibrate](/calibration/) new lenses or report missing cameras please check the [develop]({% post_url /lenslist//2999-12-31-Lenslist-master %}) lens list for a daily updated list covering the status of the current development version.

### Version ###
{% for post in site.categories.lenslist %}{% if page.url == post.url %}<a href="{{ post.url }}" class="active">[{{ post.version_tag }}]</a>&nbsp;{% else %}<a href="{{ post.url }}">[{{ post.version_tag }}]</a>&nbsp;{% endif %}{% endfor %}

