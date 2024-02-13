# Cabbagelang-leaves
The repository for Cabbagelang leaves.

## How to make a leaf

**Leaf name: example**

> **DIR** \_\_example\_\_

> > add.cbg

> example

### example.cbg

```
(import "__example__/add.cbg")
```

### \_\_example\_\_/add.cbg

```
(fun {example.add x y} {
	(+ x y)
})
```

## How to upload leaves

1. Create a pull request on [this repository](https://www.github.com/Cabbagelang-Studio/Cabbagelang-leaves).
2. Clone the repo
```
git clone https://www.github.com/Cabbagelang-Studio/Cabbagelang-leaves
```
3. Put your .zip file into the repository.
4. Wait for us to pass your pull request.

## How to install leaves

Use our package manager: **basket**

```
basket install [package]
```
