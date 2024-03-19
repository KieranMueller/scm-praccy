# ScmPraccy

A sandbox project to practice collaboration and SCM flow

# Flow

Feature branch --> development --> release --> master (production)
- PRs require review and approval
- Branch must pass 'notional' CI/CD stage before merge

## Master

Master will serve as production branch, pass CI/CD stage in release before merge to production/master branch

## Release

Pass 'notional' CI/CD stage in development branch/environment before merge to release 

## Development

Pass 'notional' CI/CD stage with feature branch running in development environment before merge to development
