<h3>Link to <a href="https://www.django-rest-framework.org/tutorial/1-serialization/">tutorial</a></h3>
<h3>Setting up</h3>
<ul>
    <li>BASE_DIR = os.path.dirname(os.path.dirname(os.path.abspath(__file__)))</li>
    <li>TEMPLATE_DIR = os.path.join(BASE_DIR, 'templates')</li>
    <li>STATIC_DIR = os.path.join(BASE_DIR, 'static')</li>
</ul>
<p>"<b>Serializer</b> class is similar to a <i>Django Form</i> class"</p>
<p>"Field flags can also control how serializer should be displayed in certain circumstances"</p>
<p>Example: <b style="color:red">{ 'base_template': 'textarea.html' }</b></p>
<p>This is the as using widget. Its widget counterpart: <b>widget=widgets.Textarea</b></p>
