# Filezilla Flatpak

## Initializing

```
git submodule update --init
```

## Building

```
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.filezillaproject.Filezilla.json
```

Then you can run it via the command line:

```
flatpak run org.filezillaproject.Filezilla
```

or just search for the installed app on your system
