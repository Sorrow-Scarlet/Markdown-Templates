<style>
:root {
  --warning-bg:rgb(238, 253, 255);
  --warning-border:rgb(238, 253, 255);
  --warning-text:rgb(0, 83, 116);
}
.github-alert {
  position: relative;
  padding: 1.25rem 2rem;
  border-radius: 8px;
  margin: 1.5rem 0;
  background: var(--warning-bg);
  border: 1px solid var(--warning-border);
  box-shadow: var(--warning-shadow);
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  display: flex;
  align-items: center;
  gap: 1.5rem;
}
.github-alert::before {
  content: '';
  position: absolute;
  top: -8px;
  left: -8px;
  right: -8px;
  bottom: -8px;
  background: linear-gradient(135deg, 
    rgba(255, 255, 255, 0.1) 0%,
    rgba(255, 255, 255, 0.05) 100%);
  z-index: -1;
  border-radius: 12px;
}
.github-alert > div {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}
.github-alert h3 {
  margin: 0;
  color: var(--warning-text);
  font-weight: 600;
  font-size: 1.1rem;
}
.github-alert p {
  margin: 0;
  color: var(--warning-text);
  line-height: 1.6;
  opacity: 0.9;
}
</style>

<!-- 正文 -->

# Lorem Ipsum

<div class="github-alert">
  <div>
    <h3>NOTICE</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas blandit metus ut commodo lacinia. </p>
  </div>
</div>

## Summary

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas blandit metus ut commodo lacinia. Cras eleifend sapien ut ornare eleifend. Cras fermentum lacinia urna, a placerat risus commodo euismod. Quisque nec semper tellus.

## Details

Cras eleifend sapien ut ornare eleifend. Cras fermentum lacinia urna, a placerat risus commodo euismod. Quisque nec semper tellus. Vivamus tristique tortor ut orci sollicitudin, non efficitur sapien tempus. Vivamus quam metus, convallis vel tellus malesuada, pharetra varius nunc. Curabitur vestibulum aliquam venenatis. Nullam fringilla placerat tempus. Nunc egestas purus et iaculis lobortis.  
Nulla efficitur dui nisl, lacinia dictum augue placerat vitae. Cras a quam tempus, porta metus varius, convallis tellus. Praesent eleifend tempus nibh, vel dignissim dolor pretium vel. Nam vitae gravida est. Pellentesque sem massa, vehicula ac hendrerit eu, fringilla at ligula.

## Todo

- Lorem Ipsum
- Lorem Ipsum
- Lorem Ipsum

Cras eleifend sapien ut ornare eleifend. Cras fermentum lacinia urna, a placerat risus commodo euismod. Quisque nec semper tellus. Vivamus tristique tortor ut orci sollicitudin, non efficitur sapien tempus. Vivamus quam metus, convallis vel tellus malesuada, pharetra varius nunc. Curabitur vestibulum aliquam venenatis. Nullam fringilla placerat tempus. Nunc egestas purus et iaculis lobortis.

## Additions

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas blandit metus ut commodo lacinia.  
Cras a quam tempus, porta metus varius, convallis tellus.

<!--邮件签名 -->
<div style="clear: both; font-size: 0; height: 0px; overflow: hidden;">&nbsp;</div>
<div class="mail_signature" spellcheck="true">
<div>

<p>Your Custom Signature Here</p>
</div>
</div>
