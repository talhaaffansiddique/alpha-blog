20 SEPT 2020
UPDATE VERSION 
<%= form_with(model: @article, local: true ) do |f| %>
    <p>
        <%= f.label :title %><br/>
        <%= f.text_field :title %>
    </p>
    <p>
        <%= f.label :description %> <br/>
        <%= f.text_area :description %>
    </p>
    <p>
        <%= f.submit %>
    </p>
<% end %>