# Pollster App (Django Crash Course)

> Python Django app to create polls with questions/choices

## Quick Start

```bash
# Install dependencies
pipenv install

cd pollster

# Serve on localhost:8000
python manage.py runserver
```

### Commands Gist

You can find all of the commands from the project here:
https://gist.github.com/bradtraversy/06538da5924882b2cf30fa6310d505b1

### Migrating to Bootstrap 5 from Bootstrap 4:

If you use Bootstrap5 cdn and don't see any votes number appearing on the results screen, then you might need to apply this minor update:

Change

`<span class="badge badge-success float-right">`

to

`<span class="badge bg-success float-end">`
