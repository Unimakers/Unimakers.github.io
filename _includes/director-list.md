{% for staff_date in site.data.staff_list %}
# L'équipe {% staff_date.date %}
<div class="container">
{% for staff_member in staff_date.staff_members %}
<div class="image-container">
<img src="{% staff_member.image %}" alt="{% staff_member.name %}">
<p>{% staff_member.name %}</p>
<p>{% staff_member.post %}</p>
{% endfor %}
{% endfor %}
