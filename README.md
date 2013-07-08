glazier-card-bootstrap
======================

A starting point for new glazier card repos


## Adding to glazier

    # in `glazier/cards/`
    ln -s your/path/to/glazier-card-bootstrap

    # in `glazier/`
    grunt ingestCards

    # in `glazier/glazier-server/`
    bundle exec rails console

    # add the Pane to the dashboard of your choosing
    >> db = Dashboard.where(repository: 'yapplabs/glazier').first
    >> db.add_pane('raycohen/glazier-card-bootstrap')
