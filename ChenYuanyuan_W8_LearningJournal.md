# Learning Activities & Resources  
This week, I focused on building a custom WordPress child theme using the Underscores (_s) framework from scratch in a server environment. I set up a local server with Ubuntu, Apache, MySQL, and PHP, installed WordPress, and created a child theme by generating the required `style.css` and `functions.php` files. I learned to enqueue parent and child theme styles properly and tested template hierarchy by overriding `header.php` to add a custom logo. After completing the practical work, I reviewed LinkedIn Learning courses like *"WordPress: Building Themes from Scratch Using Underscores"* to fill knowledge gaps, such as advanced template functions and CSS optimization techniques.  

---

# Estimated Hours  
I spent approximately 5 hours this week.  

---

# Content Insights  
Creating a child theme was a practical introduction to WordPress development. It allowed me to modify existing templates without breaking the parent theme, which is crucial for future updates. Through this process, I gained basic PHP exposure—like declaring variables with `$` and using conditional statements—and noticed similarities to Java in syntax (e.g., semicolons and curly braces). I also discovered Underscores’ built-in Sass structure and used `WP_DEBUG` to fix PHP errors during template overrides. The LinkedIn courses later taught me advanced techniques, such as optimizing CSS for performance and leveraging `get_template_part()` for reusable code.  

---

# Career/Employability/Learning Insights  
This experience directly applies to real-world projects requiring custom WordPress themes, especially for client work. Debugging template hierarchy issues (like why `front-page.php` overrides `home.php`) improved my problem-solving skills. I confirmed that my “practice-first, theory-second” learning strategy works well: hands-on coding revealed gaps in my understanding (e.g., how `add_action()` priorities work), and the tutorials later clarified those concepts. I also familiarized myself with tools like WP-CLI for server management and Chrome DevTools for live CSS edits. Moving forward, I plan to explore Underscores’ template tags and experiment with WooCommerce integration for broader web development versatility.  