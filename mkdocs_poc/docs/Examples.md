# Examples

Some content

## Tables

Data is sortable by clicking on column headers

| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

## Links

- [link](#)
- [link2](#)


## Code blocks

```powershell
Write-Host "Hello World"
```

```yaml
stages:
  - stage: stage1
    jobs:
    - job: job1
```

```json
{
    "key":"value"
}
```

## Content Tabs

=== "Unix, Powershell"

    ```
    docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .
    ```

=== "Windows (cmd)"

    ```
    docker run --rm -it -v "%cd%":/docs squidfunk/mkdocs-material new .
    ```

## Admonitions

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! tip "Tip with custom title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

## Annotations

some text (1)
{ .annotate }

1.  :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.

## Lists

### To Do List

- [x] I'm done
- [ ] To do
    * [x] Sub task Done
    * [x] Also Done
    * [ ] Need doing
- [ ] Not done

## Tooltips

Always use a Venv. :material-information-outline:{ title="Used to contain a specific Python interpreter and software libraries and binaries which are needed to support a project (library or application). These are by default isolated from software in other virtual environments and Python interpreters and libraries installed in the operating system." }

*[Venv]: Virtual ENVironment

## Diagrams

``` mermaid
erDiagram
  CUSTOMER ||--o{ ORDER : places
  ORDER ||--|{ LINE-ITEM : contains
  LINE-ITEM {
    string name
    int pricePerUnit
  }
  CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```

## Buttons

[DO NOT PRESS!](#){ .md-button .md-button--primary }

## End

The end