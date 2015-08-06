### cheatsheet for the reveal Js.

1. stat with element .reveal
2. all the slides will be inside the .slides
  e.g.
  ```html
  <div class="reveal">
    <div class="slides">
      //All slides...
    </div>
  </div>
  ```

3. Each slide will be inside `section` Target
  e.g
  ```html
  <section>
    <h2>Hello There</h2>
    <p>
      reveal.js enables you to create beautiful interactive slide decks using HTML. This presentation will show you examples of what it can do.
    </p>
  </section>

  ```  

4. Nesting of the slides will take vertical route.
5. Note: `h2` is for title of the slide.
6. `markdown` support using attribute `data-markdown`
  e.g.
  ```html
    <section data-markdown>
    ##
    </section>
  ```
7. Fragments in slides
  1. create child slide with id `fragments`.
    e.g.

    ```html
      <section id="fragments">
      </section>
    ```
  2. element can have class for framgents
      - fragment
      - fragment grow
      - fragment shrink
      - fragment fade-out
      - fragment content-visible
      - fragment highlight-red/blue
      e.g.

      ```html
        <p class="fragment grow">grow</p>
        <p class="fragment shrink">shrink</p>
        <p class="fragment fade-out">fade-out</p>

      ```
8. transitions
    ```html
     <section data-transition="slide" data-background="#4d7e65" data-background-transition="zoom">
     content
     </section>
    ```
9. Code highlight
    ```html
      <pre><code>
      alert("Hello");
      </code>
      </pre>
    ```
10. Above can be contenteditable
    ```html
      <pre><code contenteditable>
      alert("Hello");
      </code>
      </pre>
    ```  
