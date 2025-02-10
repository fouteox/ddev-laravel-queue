[![tests](https://github.com/fouteox/ddev-laravel-queue/actions/workflows/tests.yml/badge.svg)](https://github.com/fouteox/ddev-laravel-queue/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2025.svg)

* [Introduction](#introduction)
* [Installation](#installation)

## Introduction

This add-on allows you to start automatically a Laravel queues through the DDEV web service. See [official Reverb documentation](https://laravel.com/docs/11.x/queues) for more details.

## Installation

For DDEV v1.23.5 or above run

```sh
ddev add-on get fouteox/ddev-laravel-queue
```

Then restart your project

```sh
ddev restart
```

**Contributed and maintained by [fouteox](https://github.com/fouteox)**
