# Custom_Logo-header
Here is an example of code that could be used to display a dynamic logo in the header:
<header>
   <div class="logo">
      <?php if ( function_exists( 'the_custom_logo' ) ) {
         the_custom_logo();
      } else { ?>
         <h1><?php bloginfo( 'name' ); ?></h1>
      <?php } ?>
   </div>
</header>

