modules

admin ->

login page,
dashboard,
add_blogs page,
edit_blogs page,
all_blogs

category page (all, add, edit)

frontend modules
all_blogs , single_blogs

 database

name -> blogs_project

tables
users ->
id, name, email, password, profile (null) , status[active,inactive](deafault : active),token (null), created_at, updated_at

category
id,c_name, c_description, c_image(null), created_at, updated_at

blogs
id, title, description, images, category(category table id), author(users table id), status[active,inactive](deafault : active), created_at, updated_at