<h3>Links</a></h3>
<p><a href="https://www.django-rest-framework.org/tutorial/1-serialization/#where-are-we-now">Serialization</a></p>
<p><a href="https://www.django-rest-framework.org/tutorial/2-requests-and-responses/">Requests and Responses</a></p>

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

<h3>Accessing HTTP APIs</h3>
<p>In the tutorial, it is suggested to use Httpie</p>
<p>To download: <b>pip install Httpie</b></p>

<h3>Difference request.POST and request.data</h3>
<p>request.POST  # Only handles form data.  Only works for 'POST' method.</p>
<p>request.data  # Handles arbitrary data.  Works for 'POST', 'PUT' and 'PATCH' methods.</p>
<p><i>See part 2 of the <a href="https://www.django-rest-framework.org/tutorial/2-requests-and-responses/">tutorial</a></i></p>

<h3>Wrapping API Views</h3>
<p>Calling API views:</p>
<ul>
    <li><b>@api_view</b> for function-based views</li>
    <li><b>APIView</b> for class-based views</li>
</ul>