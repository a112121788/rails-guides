# Ruby on Rails 7.0 发布记

Rails 7.0 的重要变化：

* Ruby 2.7.0+ required, Ruby 3.0+ preferred

--------------------------------------------------------------------------------

## 升级到 Rails 7.0
----------------------

如果升级现有应用，在继续之前，最好确保有足够的测试覆盖度。如果尚未升级到 Rails 6.1，应该先升级到 6.1 版，确保应用能正常运行之后，再尝试升级到 Rails 6.1。升级时的注意事项参见 [从 Rails 6.1 升级到 7.0](upgrading_ruby_on_rails.html#upgrading-from-rails-6-1-to-rails-7-0)。

<a class="anchor" id="major-features"></a>

## 主要功能

Railties
--------

Please refer to the [Changelog][railties] for detailed changes.

### 移除

### 弃用

### 重要变化

Action Cable
------------

Please refer to the [Changelog][action-cable] for detailed changes.

### 移除

### 弃用

### 重要变化

Action Pack
-----------

Please refer to the [Changelog][action-pack] for detailed changes.

### 移除

### 弃用

### 重要变化

Action View
-----------

Please refer to the [Changelog][action-view] for detailed changes.

### 移除

### 弃用

### 重要变化

Action Mailer
-------------

Please refer to the [Changelog][action-mailer] for detailed changes.

### 移除

### 弃用

### 重要变化

Active Record
-------------

Please refer to the [Changelog][active-record] for detailed changes.

### 移除

*   Remove deprecated `database` kwarg from `connected_to`.

### 弃用

### 重要变化

Active Storage
--------------

Please refer to the [Changelog][active-storage] for detailed changes.

### 移除

### 弃用

### 重要变化

Active Model
------------

Please refer to the [Changelog][active-model] for detailed changes.

### 移除

### 弃用

### 重要变化

Active Support
--------------

Please refer to the [Changelog][active-support] for detailed changes.

### 移除

### 弃用

### 重要变化

Active Job
----------

Please refer to the [Changelog][active-job] for detailed changes.

### 移除

### 弃用

### 重要变化

Action Text
----------

Please refer to the [Changelog][action-text] for detailed changes.

### 移除

### 弃用

### 重要变化

Action Mailbox
----------

Please refer to the [Changelog][action-mailbox] for detailed changes.

### 移除

### 弃用

### 重要变化

Ruby on Rails Guides
--------------------

Please refer to the [Changelog][guides] for detailed changes.

### 重要变化

荣誉榜
-------

See the
[full list of contributors to Rails](https://contributors.rubyonrails.org/)
for the many people who spent many hours making Rails, the stable and robust
framework it is. Kudos to all of them.

[railties]:       https://github.com/rails/rails/blob/main/railties/CHANGELOG.md
[action-pack]:    https://github.com/rails/rails/blob/main/actionpack/CHANGELOG.md
[action-view]:    https://github.com/rails/rails/blob/main/actionview/CHANGELOG.md
[action-mailer]:  https://github.com/rails/rails/blob/main/actionmailer/CHANGELOG.md
[action-cable]:   https://github.com/rails/rails/blob/main/actioncable/CHANGELOG.md
[active-record]:  https://github.com/rails/rails/blob/main/activerecord/CHANGELOG.md
[active-storage]: https://github.com/rails/rails/blob/main/activestorage/CHANGELOG.md
[active-model]:   https://github.com/rails/rails/blob/main/activemodel/CHANGELOG.md
[active-support]: https://github.com/rails/rails/blob/main/activesupport/CHANGELOG.md
[active-job]:     https://github.com/rails/rails/blob/main/activejob/CHANGELOG.md
[action-text]:    https://github.com/rails/rails/blob/main/actiontext/CHANGELOG.md
[action-mailbox]: https://github.com/rails/rails/blob/main/actionmailbox/CHANGELOG.md
[guides]:         https://github.com/rails/rails/blob/main/guides/CHANGELOG.md