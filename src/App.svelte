<script>
  import Router from "svelte-spa-router";
  import Home from "./routes/home.svelte";
  import Portfolio from "./routes/portfolio.svelte";
  import Clock from "./components/clock.svelte";
  import Chat from "./components/chatbot.svelte";
  import Compressor from "./components/compressor.svelte";
  import Rest from "./components/rest.svelte";
  import Blog from "./routes/blog.svelte";
  import SC from "./blogs/sitecreation.svelte";
  import TH from "./blogs/thpad.svelte";
  const routes = {
    "/": Home,
    "/portfolio": Portfolio,
    "/clock": Clock,
    "/chatbot": Chat,
    "/compressor": Compressor,
    "/blog": Blog,
    "/restapi": Rest,
    "/sitecreation": SC,
    "/thinkpad": TH,
  };
</script>

<body>
  <Router {routes} />
</body>
