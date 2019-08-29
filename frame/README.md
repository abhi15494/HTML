## HTML iFrame & iFrameset

Frame are used to generate a  one HTML content within another HTML.
Best thing is that their css and js will not override each other.

> Note: An iFrame example for handling JS and CSS override issue..

### Example
    <frameset cols="w1%, w2%, ...">
	    <iframe src="www.link1.com" frameborder="0"></iframe>
	    <iframe src="www.link2.com" frameborder="0"></iframe>
	    ...
	</frameset>
