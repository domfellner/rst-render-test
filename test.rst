**Some data**

.. req:: My first requirement
   :id: req_001
   :tags: main_example

   This is an awesome requirement and it includes a nice title,
   a given id, a tag and this text as description.

.. spec:: Spec for a requirement
   :links: req_001
   :status: done
   :tags: important; main_example
   :collapse: false

   We haven't set an **ID** here, so sphinx-needs
   will generated one for us.

   But we have **set a link** to our first requirement and
   also a *status* is given.

   We also have set **collapse** to false, so that all
   meta-data is shown directly under the title.

**Some text**

Wohooo, we have created :need:`req_001`,
which is linked by :need_incoming:`req_001`.
