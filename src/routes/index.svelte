<script>
	import Header from "$lib/Header.svelte";
	import Nav from "$lib/Nav.svelte";
	import Footer from "$lib/Footer.svelte";
</script>

<Header />

<Nav />

<main>
	<h1>
    YouTube’s Biggest Channels
      </h1>
    </div>
<nav>
  <a href="index.html">Home</a>
  <a href="vs-code.html">Music</a>
  <a href="github.html">Education</a>
  <a href="netlify.html">Entertainment</a>
</nav>

<main></main>
    <h2>
      What is YouTube?
    </h2>
   
    <p>
      YouTube is a free video sharing website on the internet. The website lets people upload, view, and share videos. YouTube was started on February 14, 2005 by three former workers of PayPal. Google (a search engine company) has owned and operated YouTube since 2006. YouTube now carries paid advertisements on all pages.

      Videos can be rated with likes or dislikes, and viewers can subscribe to channels they like. Videos can be commented on if viewers log into their own accounts. The number of times a video has been watched, known as "views", are shown.
      
      Many different types of videos can be put onto the website, such as educational content, animations, and events.
      
    </p>
  </main>
    <style>
        * {
          font-family: sans-serif;
        }
      
        h1 {
          text-align: center;
        }
        
         /* CSS property for nevigation menu */ 
         .nav_menu { 
            overflow: hidden; 
            background-color: #5d2a42; 
        }
       }

      main {
        background-color:deeppink;
      }
      </style>
      <style>
        header { grid-area: h; }
        nav    { grid-area: n; }
        main   { grid-area: m; }
      
        main {
          display: grid;
          grid: "h    h    h  "  
                "n    h    h  " 
                "m    m    m  " 
                /1fr  fr  1fr;
        }
		</style>
		