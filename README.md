<h4> Hello everyone, I'm Maksim</a> 
Python web-developer since 2022 year.
  
![](https://www.codewars.com/users/RichMan24/badges/small)

<div class="col-lg-4 col-md-6 p-4">
                <div class="card border-primary rounded custom-shadow">
                    <img src="{{ product.image }}" class="card-img-top" alt="...">
                    <div class="card-body">
                        <a href="../goods/product.html">
                            <p class="card-title">{{ product.name }}</p>
                        </a>
                        <p class="card-text text-truncate">{{ product.description }}</p>
                        <p class="product_id">id: 02265</p>
                        <div class="d-flex justify-content-between">
                            {% comment %} <p><s>100</s> $</p> {% endcomment %}
                            {% comment %} <p><strong>90.00 $</strong></p> {% endcomment %}
                            {% comment %} <span class="badge bg-warning text-dark">Скидка 10.00 %</span> {% endcomment %}
                            <p><strong>{{ product.price }}</strong></p>
                            <a href="#" class="btn add-to-cart">
                                <img class="mx-1" src="{% static "deps/icons/cart-plus.svg" %}" alt="Catalog Icon"
                                    width="32" height="32">
                            </a>
                        </div>
                    </div>
                </div>
            </div>

My tecknology stack:

'python 3.7+' 'native SQL' 'pandas' 'numpy' 'beautiful soup'
'aiogram 3' 'fast' 'api' 'keras' 'pytorch' 'requests' 'regex (:re)'
'sqlite3' 'postgresql'



<!---
Richman-24/Richman-24 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
