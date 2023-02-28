# --------------------
# test
# --------------------
# is_app_source_changed = !git.modified_files.grep(/^app/).empty?
# is_app_test_changed = !git.modified_files.grep(/^app\/spec/).empty?

# if is_app_source_changed && !is_app_test_changed
#   message('railsのコードの変更があるけど、関連するテストが無いみたいだね。テストの追加・修正が必要ないか検討してね！')
# end

# is_c9l_source_changed = !git.modified_files.grep(/^connect\/connectmail/).empty?
# is_c9l_test_changed = !git.modified_files.grep(/^connect\/connectmail\/spec/).empty?

# if is_c9l_source_changed && !is_c9l_test_changed
#   message('railsのコードの変更があるけど、関連するテストが無いみたいだね。テストの追加・修正が必要ないか検討してね！')
# end

# --------------------
# base branch
# --------------------
# is_to_release = github.branch_for_base.start_with?('release/')
# is_from_hotfix = github.branch_for_head.start_with?('hotfix/')
# is_from_early_release = github.branch_for_head.start_with?('early-release/')

# if is_from_hotfix && !is_to_release
#   fail('hotfixブランチだけど、releaseブランチに向いてないかな。hotfixはreleaseブランチに向けて出してほしいな！')
# end

# if is_from_early_release && !is_to_release
#   fail('early-releaseブランチだけど、releaseブランチに向いてないみたいだね。early-releaseはreleaseブランチに向けて出してね！')
# end

# if !is_from_hotfix && !is_from_early_release && is_to_release
#   fail('early-releaseブランチでもhotfixブランチでもないけど、releaseブランチに向いてるみたいだよ。releaseブランチに向けないでね！')
# end

# --------------------
# diff size
# --------------------
# is_big_pr = git.lines_of_code > 500

# if is_big_pr
#   message('PRの変更量が多いみたいだよ！PRの分割を検討してみてね！')
# end
