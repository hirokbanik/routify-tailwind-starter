<script>
  import { Router } from "@sveltech/routify";
  import { routes } from "../.routify/routes";
</script>

<style  global>
  /* purgecss start ignore */
  @import 'tailwindcss/base';

  @import 'tailwindcss/components';
  /* purgecss end ignore */

  @import 'tailwindcss/utilities';

  /* Don't forget to remove unused styles in global.css */
  @import "../static/global.css";
</style>

<Router {routes} />