```liquid
{% comment %}
This code snippet is designed for a Shopify custom Liquid field.
{% endcomment %}

<div class="custom-content">
  <h2>{{ section.settings.heading }}</h2>
  <p>{{ section.settings.description }}</p>
  <a href="{{ section.settings.link_url }}" class="btn">
    {{ section.settings.link_text }}
  </a>
</div>

<style>
  .custom-content {
    text-align: center;
    padding: 20px;
    background-color: #f9f9f9;
  }
  .custom-content .btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
  }
  .custom-content .btn:hover {
    background-color: #0056b3;
  }
</style>