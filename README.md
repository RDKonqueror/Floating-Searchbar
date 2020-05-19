# Floating-Searchbar
A searchbar with floating animation using HTML, CSS, Javascript and cssanimation.io

My edit:
<code>
<pre>
.leRencontre span {
    animation: leRencontre 4s;
    animation-iteration-count: infinite;
}
@keyframes leRencontre {
    0%, 33%, 100% {
        transform-origin: bottom;
        animation-timing-function: cubic-bezier(.17,.67,.79,1.83)
    }
    33% {
        transform: translateY(-5px) rotate(-5deg);
    }
    66% {
        transform: translateY(5px) rotate(5deg);
    }
}
</pre>
</code>



<img src="https://github.com/RDKonqueror/Floating-Searchbar/blob/master/shot.png" width="766px" height="442px" />
