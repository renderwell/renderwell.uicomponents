# The Grid

<p class="lead">Objectively innovate empowered manufactured products whereas parallel platforms. Holisticly predominate extensible testing procedures for reliable supply chains.</p>

---

## Usage

```html
<div class="row">
  <div class="small-6 medium-4 large-3 columns">...</div>
  <div class="small-6 medium-8 large-9 columns">...</div>
</div>
```

<div class="row display">
  <div class="small-12 large-4 columns">4</div>
  <div class="small-12 large-4 columns">4</div>
  <div class="small-12 large-4 columns">4</div>
</div>
<div class="row display">
  <div class="small-12 large-3 columns">3</div>
  <div class="small-12 large-6 columns">6</div>
  <div class="small-12 large-3 columns">3</div>
</div>
<div class="row display">
  <div class="small-12 large-2 columns">2</div>
  <div class="small-12 large-8 columns">8</div>
  <div class="small-12 large-2 columns">2</div>
</div>
<div class="row display">
  <div class="small-12 large-3 columns">3</div>
  <div class="small-12 large-9 columns">9</div>
</div>
<div class="row display">
  <div class="small-12 large-4 columns">4</div>
  <div class="small-12 large-8 columns">8</div>
</div>
<div class="row display">
  <div class="small-12 large-5 columns">5</div>
  <div class="small-12 large-7 columns">7</div>
</div>
<div class="row display">
  <div class="small-12 large-6 columns">6</div>
  <div class="small-12 large-6 columns">6</div>
</div>

---

## Nesting Rows

In the Grid you can nest columns down as far as you'd like. Just embed rows inside columns and go from there. Each embedded row can contain up to 12 columns.

```html
<div class="row">
  <div class="small-8 columns">8
    <div class="row">
      <div class="small-8 columns">8 Nested
        <div class="row">
          <div class="small-8 columns">8 Nested Again</div>
          <div class="small-4 columns">4</div>
        </div>
      </div>
      <div class="small-4 columns">4</div>
    </div>
  </div>
  <div class="small-4 columns">4</div>
</div>
```

<div class="row display">
  <div class="small-8 columns">8
    <div class="row">
      <div class="small-8 columns">8 Nested
        <div class="row">
          <div class="small-8 columns">8 Nested Again</div>
          <div class="small-4 columns">4</div>
        </div>
      </div>
      <div class="small-4 columns">4</div>
    </div>
  </div>
  <div class="small-4 columns">4</div>
</div>

---

## Small Grid

As you've probably noticed in the examples above, you have access to a small, medium, and large grid. If you know that your grid structure will be the same for small devices as it will be on large devices, just use the small grid. You can override your small grid classes by adding medium or large grid classes.

```html
<div class="row">
  <div class="small-2 columns">2</div>
  <div class="small-10 columns">10, last</div>
</div>
<div class="row">
  <div class="small-3 columns">3</div>
  <div class="small-9 columns">9, last</div>
</div>
```

<div class="row display">
  <div class="small-2 columns">2</div>
  <div class="small-10 columns">10, last</div>
</div>
<div class="row display">
  <div class="small-3 columns">3</div>
  <div class="small-9 columns">9, last</div>
</div>



# Colors

<p class="lead">Below you can find the different values we created that support the primary color variable you can change at any time in <code>\_settings.scss</code></p>

---

<div class="row up-1 medium-up-3 large-up-5">
  <div class="column">
    <div class="color-block">
      <span style="background: #2199e8"></span>
      #2199e8
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #3adb76"></span>
      #3adb76
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #ffae00"></span>
      #ffae00
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #ec5840"></span>
      #ec5840
    </div>
  </div>
  <div class="column">
    <div class="color-block">
      <span style="background: #0a0a0a"></span>
      #0a0a0a
    </div>
  </div>
</div>



# Typography

<p class="lead">This design uses Helvetica Neue for headings and paragraph text.</p>

---

## Headings

Headings are used to denote different sections of content, usually consisting of related paragraphs and other HTML elements. They range from h1 to h6 and should be styled in a clear hierarchy (i.e., largest to smallest)

---

## Paragraphs

Paragraphs are groups of sentences, each with a lead (first sentence) and transition (last sentence). They are block level elements, meaning they stack vertically when repeated. Use them as such.

---

<h1>Heading Level 1</h1>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h2>Heading Level 2</h2>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h3>Heading Level 3</h3>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h4>Heading Level 4</h4>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h5>Heading Level 5</h5>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.

<h6>Heading Level 6</h6>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quibusdam ratione sunt dolorum, qui illo maxime doloremque accusantium cum libero eum, a optio odio placeat debitis ullam aut non distinctio.



# Buttons

<p class="lead">Buttons are tied to an action of some kind, whether that button is on a cheese dispenser or launches the rocket that you're strapped to. On the web, we follow similar conventions.</p>

---

## Primary Buttons

These buttons are primary calls to action and should be used sparingly. Their size can be adjusted with the `.tiny`, `.small`, and `.large` classes.

```html_example
<a href="#" class="primary large button">Large button</a>
<a href="#" class="primary button">Regular button</a>
<a href="#" class="primary small button">Small button</a>
<a href="#" class="primary tiny button">Tiny button</a>
```

---

## Secondary Buttons

These buttons are used for less important, secondary actions on a page.

```html_example
<a href="#" class="secondary large button">Large button</a>
<a href="#" class="secondary button">Regular button</a>
<a href="#" class="secondary small button">Small button</a>
<a href="#" class="secondary tiny button">Tiny button</a>
```



# Forms

<p class="lead">Use forms to allow users to interact with the site and provide information to the company.</p>

---

## Elements of a Form

A form should be marked up using its default HTML properties. The ones we make use of include (in hierarchical order):

- Form
- Label
- Input
- Select
- Text area
- Button

---

## How to Use

Make forms great and easy to use with the following rules:

- Wrap checkboxes and radio buttons within labels for larger hit areas, and be sure to set the for, name, and id attributes for all applicable elements.
- Series of checkboxes and radio buttons below within a `<ul class="inline-list">`.
- Before selecting any set of fields to use for a required input, explore other options (e.g., radio buttons over select lists).

---

## Form Layouts

Form elements in Foundation are styled based on their type attribute rather than a class. Inputs in Foundation have another major advantage — they are full width by default. That means that inputs will run as wide as the column that contains them. However, you have two options which make these forms extremely versatile:

- You can size inputs using column sizes, like `.medium-6`, `.small-6`.
- You can create row elements inside your form and use columns for the form, including inputs, labels and more. Rows inside a form inherit some special padding to even up input spacing.

---

## Form Example

```html_example
<form>
  <div class="row">
    <div class="large-12 columns">
      <label>Label</label>
      <input type="text" placeholder="placeholder">
    </div>
  </div>
  <div class="row">
    <div class="large-6 columns">
      <label>Label</label>
      <input type="text" placeholder="placeholder">
    </div>
    <div class="large-6 columns">
      <div class="row collapse">
        <label>Label</label>
        <div class="input-group">
          <input class="input-group-field" type="text" placeholder="placeholder">
          <span class="input-group-label">.com</span>
        </div>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="large-12 columns">
      <label>Select Box</label>
      <select>
        <option value="good">Good</option>
        <option value="better">Better</option>
        <option value="best">Best</option>
      </select>
    </div>
  </div>
  <div class="row">
    <div class="large-6 columns">
      <label>Choose Your Favorite</label>
      <input type="radio" name="radio1" value="radio1" id="radio1"><label for="radio1">Red</label>
      <input type="radio" name="radio2" value="radio2" id="radio2"><label for="radio2">Blue</label>
    </div>
    <div class="large-6 columns">
      <label>Check these out</label>
      <input id="checkbox1" type="checkbox"><label for="checkbox1">Checkbox 1</label>
      <input id="checkbox2" type="checkbox"><label for="checkbox2">Checkbox 2</label>
    </div>
  </div>
  <div class="row">
    <div class="large-12 columns">
      <label>Textarea Label</label>
      <textarea placeholder="placeholder"></textarea>
    </div>
  </div>
</form>
```



# Card

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
<div class="card" style="width: 300px;">
  <div class="card-divider">
    This is a header
  </div>
  <img src="assets/img/rectangle-1.jpg">
  <div class="card-section">
    <h4>This is a card.</h4>
    <p>It has an easy to override visual style, and is appropriately subdued.</p>
  </div>
</div>
```



# Discreet Card

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
<div class="card card--discreet text-center" style="width: 300px;">
  <img src="assets/img/rectangle-2.jpg">
  <div class="card-divider">
    <h4>This is a card.</h4>
  </div>
  <div class="card-section">
    <p>It has an easy to override visual style, and is appropriately subdued.</p>
  </div>
</div>
```



# Cards in a grid

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
<div class="row">
    <div class="column medium-4">
        <div class="card card--discreet text-center">
          <img src="assets/img/rectangle-2.jpg">
          <div class="card-divider">
            <h4>This is a card.</h4>
          </div>
          <div class="card-section">
            <p>Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition.</p>
          </div>
        </div>
    </div>
    <div class="column medium-4">
        <div class="card card--discreet text-center">
          <img src="assets/img/rectangle-2.jpg">
          <div class="card-divider">
            <h4>This is a card.</h4>
          </div>
          <div class="card-section">
            <p>Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment. Dramatically engage top-line web services vis-a-vis cutting-edge deliverables.</p>
          </div>
        </div>
    </div>
    <div class="column medium-4">
        <div class="card card--discreet text-center">
          <img src="assets/img/rectangle-2.jpg">
          <div class="card-divider">
            <h4>This is a card.</h4>
          </div>
          <div class="card-section">
            <p>Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing. Interactively procrastinate high-payoff content without backward-compatible data.</p>
          </div>
        </div>
    </div>
</div>
```



# Card: Prescient Skin

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
<div class="row">
    <div class="column medium-4">
        <div class="card card--discreet card--prescient_skin expand-on-hover-container invert-on-hover-container text-center">
            <div class="card-divider">
                <i class="icon-agile circled-item expand-on-hover-contained invert-on-hover-contained"></i>
            </div>

            <div class="card-section">
                <h4>Solutions</h4>
                <div class="small-break"></div>
                <p>We assess, plan, design and build world-class intranets and digital workplaces. With 200+ clients, we are the most experienced, dedicated intranet consulting firm.</p>
                <ul style="list-style: none">
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <div class="column medium-4">
        <div class="card card--discreet card--prescient_skin expand-on-hover-container invert-on-hover-container text-center">
            <div class="card-divider">
                <i class="icon-agile circled-item expand-on-hover-contained invert-on-hover-contained"></i>
            </div>

            <div class="card-section">
                <h4>Solutions</h4>
                <div class="small-break"></div>
                <p>We assess, plan, design and build world-class intranets and digital workplaces. With 200+ clients, we are the most experienced, dedicated intranet consulting firm.</p>
                <ul style="list-style: none">
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <div class="column medium-4">
        <div class="card card--discreet card--prescient_skin expand-on-hover-container invert-on-hover-container text-center">
            <div class="card-divider">
                <i class="icon-agile circled-item expand-on-hover-contained invert-on-hover-contained"></i>
            </div>

            <div class="card-section">
                <h4>Solutions</h4>
                <div class="small-break"></div>
                <p>We assess, plan, design and build world-class intranets and digital workplaces. With 200+ clients, we are the most experienced, dedicated intranet consulting firm.</p>
                <ul style="list-style: none">
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                    <li>
                        <a href="#0" target="_self" title="">Intranet Consulting</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</div>
```



# Circled content

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
    <div class="circled--small">
        Leverage agile frameworks to provide a robust synopsis for high level overviews.
    </div>
    <div class="circled-item--small">
        agile
    </div>
    <div class="circled-element--small">
        <span>agile frameworks</span>
    </div>
    <div class="circled-element--small text-center">
        <span>agile frameworks</span>
    </div>

    <br />

    <div class="circled">
        Leverage agile frameworks to provide a robust synopsis for high level overviews.
    </div>
    <div class="circled-item">
        agile
    </div>
    <div class="circled-element">
        <span>agile frameworks</span>
    </div>
    <div class="circled-element text-center">
        <span>agile frameworks</span>
    </div>

    <br />

    <div class="circled--large">
        Leverage agile frameworks to provide a robust synopsis for high level overviews.
    </div>
    <div class="circled-item--large">
        agile
    </div>
    <div class="circled-element--large">
        <span>agile frameworks</span>
    </div>
    <div class="circled-element--large text-center">
        <span>agile frameworks</span>
    </div>
```



# Expand on hover

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
    <div class="circled-item expand-on-hover">
        agile
    </div>
    <div class="circled-element text-center expand-on-hover">
        <span>agile frameworks</span>
    </div>
    <div class="expand-on-hover text-center" style="width: 200px; padding: 5px 0; border: 1px solid red;">
        agile frameworks
    </div>

    <br />

    <div class="circled-item expand-on-hover--large">
        agile
    </div>

    <br />

    <div class="expand-on-hover-container text-center" style="width: 300px; padding: 15px 15px 0 15px; border: 1px solid black">
        <div class="circled-element expand-on-hover-contained">
            <span>agile</span>
        </div>
        <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications.</p>
    </div>
```



# Invert on hover

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
    <div class="circled-item expand-on-hover invert-on-hover">
        agile
    </div>
    <div class="circled-item expand-on-hover invert-on-hover_example-skin">
        agile
    </div>
```



# Media

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
<section class="media">
    <a href="#0" class="media__media">
        <img src="/assets/img/flower_02.jpg">
    </a>

    <div class="media__content">
        <header>
            <h3>Etiam consectetur ultrices nibh</h3>
        </header>

        <p>In lacus massa, efficitur quis elit a, porttitor tristique tellus. Vivamus ultrices tellus sem.</p>
        <p>Proin magna felis, bibendum at iaculis vel, varius vitae orci. Maecenas tempor sollicitudin mattis.</p>
        <p>Nullam velit arcu, iaculis quis bibendum eget, ultricies vel nulla. Curabitur eu magna consequat.</p>
    </div>
</section>
```



# Media (content led)

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
<section class="media">
    <a href="#0" class="media__media--ext">
        <img src="/assets/img/flower_03.jpg">
    </a>

    <div class="media__content">
        <header>
            <h3>Etiam consectetur ultrices nibh</h3>
        </header>

        <p>In lacus massa, efficitur quis elit a, porttitor tristique tellus. Vivamus ultrices tellus sem.</p>
        <p>Proin magna felis, bibendum at iaculis vel, varius vitae orci. Maecenas tempor sollicitudin mattis.</p>
        <p>Nullam velit arcu, iaculis quis bibendum eget, ultricies vel nulla. Curabitur eu magna consequat.</p>
    </div>
</section>
```



# New Section

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora omnis suscipit id ut laborum recusandae molestias hic aliquid **expedita!** [Non dicta](zurb.com), autem obcaecati error, id ab voluptate unde culpa nulla.

```html_example
<a href="#" class="button">Button</a>
<a href="#" class="button">Button</a>
<a href="#" class="button">Button</a>
```
