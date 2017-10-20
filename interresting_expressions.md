
                    Deleting content in brackets
                    
preg_replace('/(({){1,1}(\w)*(}){1,1})*/s', '$2$4', '/user/{id}/post/{post_id}'); // /user/{}/post/{}                    