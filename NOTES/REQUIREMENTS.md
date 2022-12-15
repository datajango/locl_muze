# REQUIREMENTS.md
1. As a user I need a way to view music stored on one or more harddrives on my computers.
    1. If the application is running on more than one computer, it will be able to communicate between computers using a network interface and communication protocol. This will allow computers to share music index information across a network.
    1. Maybe MQTT can be used.
1. As a user I need to index all FLAC and MP3 file format files.
1. Files should be display using a tree.
1. In the treeview, there should be major categories of:
    1. Album
    1. Artist
    1. Genre
    1. Year
    1. Matched
    1. Unmatched
1. As a user I need a way to manage categories in the tree view.
    1. add a category
        1. Allows searching and adding any combination of ID3 tag
    1. edit a category
    1. remove a category
    1. duplicate a category
    1. save all categories and their details to JSON file.
1. What is a category?
    1. A category can be a set of key value pairs.
    1. Example: All files tagged with "Easy Listening"
    1. Example: All files tagged with "Swedish Death Metal"
    1. Example: All files with a ID3 tag of year published of 1978
1. As a user I need a way to entire a remote I ID3 Tag database.
    1. Create a new Remote ID3 Tag database entry
        1. host
        1. port
        1. API Key info
    1. Edit an existing Remote ID3 Tag database entry
    1. Remove a existing Remote ID3 Tag database entry




