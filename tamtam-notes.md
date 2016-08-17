

<!-- <a href="/posts/<%= post.id %>">blah</a> -->
<!-- # <%= link_to post.title, "/posts/#{post.id}" %>  -->

<% @posts.each do |post| %>
  <div><%= link_to post.title, post_path(post.id) %></div>
<% end %>






