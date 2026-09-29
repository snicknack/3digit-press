# 3DIGIT Press Images

Press-release pictures for 3DIGIT products — logos, product shots and screenshots.

**[SynthSYS press kit →](synthsys/README.md)** every SynthSYS picture with its direct link.

## Folders

| Folder | Contents |
| --- | --- |
| `logos/` | 3DIGIT and product logos |
| `synthsys/` | SynthSYS screenshots and product shots |
| `racksys/` | RackSYS screenshots and product shots |
| `authsys/` | AuthSYS screenshots and product shots |

Add a new folder for any other product.

## Adding pictures

**In the browser:** open a folder on GitHub → **Add file → Upload files** → drag the pictures in → **Commit changes**.

**From the Mac:**

```bash
cd ~/3digit-press
cp ~/Desktop/my-shot.png synthsys/
git add . && git commit -m "Add SynthSYS shot" && git push
```

## Linking to a picture

Every picture has a direct link you can put in a press release or email:

```
https://raw.githubusercontent.com/snicknack/3digit-press/main/<folder>/<file>
```

For example `https://raw.githubusercontent.com/snicknack/3digit-press/main/synthsys/main-window.png`.

Tips: use lowercase file names with dashes (no spaces), and PNG or JPG. Keep single files under 25 MB so the browser upload accepts them.
