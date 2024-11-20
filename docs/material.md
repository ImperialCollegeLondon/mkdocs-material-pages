---
title: Material Features
---


## Admonitions

!!! note
    This is a basic note admonition

!!! tip "Custom Title"
    You can customize the title of admonitions

!!! info
    Here's some information

!!! warning
    Watch out for this

!!! danger
    This is a dangerous operation

??? note "Expandable Note"
    This note starts collapsed

???+ tip "Expanded by Default"
    This note starts expanded

## Content Tabs

=== "Tab 1"
    This is content in the first tab

=== "Tab 2"
    This content shows in the second tab

=== "Tab 3"
    And this is in the third tab

### Code in Tabs

=== "Python"
    ```python
    def hello_world():
        print("Hello from Python!")
    ```

=== "JavaScript"
    ```javascript
    function helloWorld() {
        console.log("Hello from JavaScript!");
    }
    ```

=== "Java"
    ```java
    public class HelloWorld {
        public static void main(String[] args) {
            System.out.println("Hello from Java!");
        }
    }
    ```

## Annotations

Here's a line with an annotation. (1)
{ .annotate }

And another interesting point. (2)
{ .annotate }

1.  This explains the first annotation
2.  And this explains the second one

### Code with Annotations

```python
def process_data(data):  # (1)
    result = data * 2    # (2)
    return result        # (3)!
```

1.  Function takes a data parameter
2.  Multiplies the input by 2
3.  Returns the processed result, hide the hashtag

## Grids

<div class="grid cards" markdown>

- :fontawesome-brands-html5: __HTML__ – HyperText Markup Language
- :fontawesome-brands-js: __JavaScript__ – Programming Language
- :fontawesome-brands-css3: __CSS__ – Cascading Style Sheets
- :fontawesome-brands-python: __Python__ – Programming Language

</div>


## Combined Example

!!! example "Authentication Methods"

    === "API Keys"
        ```python
        def authenticate(api_key):  # (1)
            return {"Authorization": f"Bearer {api_key}"}  # (2)
        ```

        1.  Takes API key as input
        2.  Returns formatted header

    === "OAuth"
        ```python
        def oauth_auth(client_id):  # (1)
            return {"client_id": client_id}  # (2)
        ```

        1.  Takes client ID
        2.  Returns oauth header

    === "Basic Auth"
        ```python
        def basic_auth(username, password):  # (1)
            return {"Authorization": encode_basic(username, password)}  # (2)
        ```

        1.  Takes credentials
        2.  Returns encoded header