## Licensed under the Apache License, Version 2.0 (the "License"); you may not
## use this file except in compliance with the License. You may obtain a copy of
## the License at
##
##   http://www.apache.org/licenses/LICENSE-2.0
##
## Unless required by applicable law or agreed to in writing, software
## distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
## WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
## License for the specific language governing permissions and limitations under
## the License.

SUBDIRS = \
    couch_dbupdates \
    couch_index \
    couch_mrview \
    couch_plugins \
    couch_replicator \
    couchdb \
    ejson \
    erlang-oauth \
    etap \
    ibrowse \
    mochiweb \
    snappy \
    couchjs-node

EXTRA_DIST = \
    $(MY_FIRST_COUCHDB_PLUGIN_FILES) \
    $(FAUXTON_FILES)

MY_FIRST_COUCHDB_PLUGIN_FILES = \
  my-first-couchdb-plugin/.gitignore \
  my-first-couchdb-plugin/Makefile \
  my-first-couchdb-plugin/priv/default.d/my_first_couchdb_plugin.ini \
  my-first-couchdb-plugin/README.md \
  my-first-couchdb-plugin/src/my_first_couchdb_plugin.app.src \
  my-first-couchdb-plugin/src/my_first_couchdb_plugin.erl \
  my-first-couchdb-plugin/test/my_first_couchdb_plugin_tests.erl

FAUXTON_FILES = \
    fauxton/app/addons/activetasks/assets/less/activetasks.less \
    fauxton/app/addons/activetasks/base.js \
    fauxton/app/addons/activetasks/resources.js \
    fauxton/app/addons/activetasks/routes.js \
    fauxton/app/addons/activetasks/templates/detail.html \
    fauxton/app/addons/activetasks/templates/table.html \
    fauxton/app/addons/activetasks/templates/tabledetail.html \
    fauxton/app/addons/activetasks/templates/tabs.html \
    fauxton/app/addons/activetasks/tests/viewsSpec.js \
    fauxton/app/addons/activetasks/views.js \
    fauxton/app/addons/auth/base.js \
    fauxton/app/addons/auth/resources.js \
    fauxton/app/addons/auth/routes.js \
    fauxton/app/addons/auth/assets/less/auth.less \
    fauxton/app/addons/auth/templates/change_password.html \
    fauxton/app/addons/auth/templates/create_admin.html \
    fauxton/app/addons/auth/templates/login.html \
    fauxton/app/addons/auth/templates/nav_dropdown.html \
    fauxton/app/addons/auth/templates/nav_link_title.html \
    fauxton/app/addons/auth/templates/noAccess.html \
    fauxton/app/addons/auth/test/baseSpec.js \
    fauxton/app/addons/compaction/assets/less/compaction.less \
    fauxton/app/addons/compaction/templates/compact_view.html \
    fauxton/app/addons/compaction/templates/layout.html \
    fauxton/app/addons/compaction/base.js \
    fauxton/app/addons/compaction/resources.js \
    fauxton/app/addons/compaction/routes.js \
    fauxton/app/addons/compaction/views.js \
    fauxton/app/addons/config/base.js \
    fauxton/app/addons/config/resources.js \
    fauxton/app/addons/config/views.js \
    fauxton/app/addons/config/routes.js \
    fauxton/app/addons/config/templates/modal.html \
    fauxton/app/addons/config/templates/dashboard.html \
    fauxton/app/addons/config/templates/item.html \
    fauxton/app/addons/config/tests/resourcesSpec.js \
    fauxton/app/addons/contribute/base.js \
    fauxton/app/addons/exampleAuth/base.js \
    fauxton/app/addons/exampleAuth/templates/noAccess.html \
    fauxton/app/addons/logs/base.js \
    fauxton/app/addons/logs/resources.js \
    fauxton/app/addons/logs/routes.js \
    fauxton/app/addons/logs/templates/dashboard.html \
    fauxton/app/addons/logs/templates/filterItem.html \
    fauxton/app/addons/logs/templates/sidebar.html \
    fauxton/app/addons/logs/tests/logSpec.js \
    fauxton/app/addons/permissions/assets/less/permissions.less \
    fauxton/app/addons/permissions/base.js \
    fauxton/app/addons/permissions/resources.js \
    fauxton/app/addons/permissions/routes.js \
    fauxton/app/addons/permissions/templates/item.html \
    fauxton/app/addons/permissions/templates/permissions.html \
    fauxton/app/addons/permissions/templates/section.html \
    fauxton/app/addons/permissions/tests/resourceSpec.js \
    fauxton/app/addons/permissions/tests/viewsSpec.js \
    fauxton/app/addons/permissions/views.js \
    fauxton/app/addons/plugins/base.js \
    fauxton/app/addons/plugins/resources.js \
    fauxton/app/addons/plugins/routes.js \
    fauxton/app/addons/plugins/templates/plugins.html \
    fauxton/app/addons/replication/assets/less/replication.less \
    fauxton/app/addons/replication/base.js \
    fauxton/app/addons/replication/resources.js \
    fauxton/app/addons/replication/route.js \
    fauxton/app/addons/replication/templates/form.html \
    fauxton/app/addons/replication/templates/progress.html \
    fauxton/app/addons/replication/tests/replicationSpec.js \
    fauxton/app/addons/replication/views.js \
    fauxton/app/addons/stats/assets/less/stats.less \
    fauxton/app/addons/stats/base.js \
    fauxton/app/addons/stats/resources.js \
    fauxton/app/addons/stats/routes.js \
    fauxton/app/addons/stats/templates/by_method.html \
    fauxton/app/addons/stats/templates/pie_table.html \
    fauxton/app/addons/stats/templates/stats.html \
    fauxton/app/addons/stats/templates/statselect.html \
    fauxton/app/addons/stats/views.js \
    fauxton/app/addons/styletests/base.js \
    fauxton/app/addons/styletests/resources.js \
    fauxton/app/addons/styletests/routes.js \
    fauxton/app/addons/styletests/views.js \
    fauxton/app/addons/styletests/templates/theme.html \
    fauxton/app/addons/verifyinstall/views.js \
    fauxton/app/addons/verifyinstall/resources.js \
    fauxton/app/addons/verifyinstall/base.js \
    fauxton/app/addons/verifyinstall/routes.js \
    fauxton/app/addons/verifyinstall/templates/main.html \
    fauxton/app/addons/verifyinstall/assets/less/verifyinstall.less \
    fauxton/app/core/api.js \
    fauxton/app/core/auth.js \
    fauxton/app/core/base.js \
    fauxton/app/core/couchdbSession.js \
    fauxton/app/core/layout.js \
    fauxton/app/core/routeObject.js \
    fauxton/app/core/router.js \
    fauxton/app/core/utils.js \
    fauxton/app/core/tests/layoutSpec.js \
    fauxton/app/core/tests/routeObjectSpec.js \
    fauxton/app/app.js \
    fauxton/app/config.js \
    fauxton/app/helpers.js \
    fauxton/app/initialize.js.underscore \
    fauxton/app/load_addons.js.underscore \
    fauxton/app/main.js \
    fauxton/app/addons/databases/base.js \
    fauxton/app/addons/databases/resources.js \
    fauxton/app/addons/databases/routes.js \
    fauxton/app/addons/databases/views.js \
    fauxton/app/addons/databases/tests/resourcesSpec.js \
    fauxton/app/addons/documents/base.js \
    fauxton/app/addons/documents/resources.js \
    fauxton/app/addons/documents/routes.js \
    fauxton/app/addons/documents/tests/resourcesSpec.js \
    fauxton/app/addons/documents/views.js \
    fauxton/app/addons/fauxton/base.js \
    fauxton/app/addons/fauxton/components.js \
    fauxton/app/addons/fauxton/resizeColumns.js \
    fauxton/app/addons/fauxton/tests/baseSpec.js \
    fauxton/app/addons/fauxton/tests/navbarSpec.js \
    fauxton/app/addons/fauxton/tests/paginateSpec.js \
    fauxton/app/addons/pouchdb/base.js \
    fauxton/app/addons/pouchdb/pouch.collate.js \
    fauxton/app/addons/pouchdb/pouchdb.mapreduce.js \
    fauxton/app/addons/databases/templates/item.html \
    fauxton/app/addons/databases/templates/list.html \
    fauxton/app/addons/databases/templates/newdatabase.html \
    fauxton/app/addons/databases/templates/sidebar.html \
    fauxton/app/addons/documents/templates/advanced_options.html \
    fauxton/app/addons/documents/templates/all_docs_item.html \
    fauxton/app/addons/documents/templates/all_docs_layout.html \
    fauxton/app/addons/documents/templates/all_docs_list.html \
    fauxton/app/addons/documents/templates/all_docs_number.html \
    fauxton/app/addons/documents/templates/changes.html \
    fauxton/app/addons/documents/templates/ddoc_info.html \
    fauxton/app/addons/documents/templates/delete_database_modal.html \
    fauxton/app/addons/documents/templates/design_doc_selector.html \
    fauxton/app/addons/documents/templates/doc.html \
    fauxton/app/addons/documents/templates/doc_field_editor.html \
    fauxton/app/addons/documents/templates/doc_field_editor_tabs.html \
    fauxton/app/addons/documents/templates/duplicate_doc_modal.html \
    fauxton/app/addons/documents/templates/edit_tools.html \
    fauxton/app/addons/documents/templates/index_menu_item.html \
    fauxton/app/addons/documents/templates/index_row_docular.html \
    fauxton/app/addons/documents/templates/index_row_tabular.html \
    fauxton/app/addons/documents/templates/jumpdoc.html \
    fauxton/app/addons/documents/templates/search.html \
    fauxton/app/addons/documents/templates/sidebar.html \
    fauxton/app/addons/documents/templates/tabs.html \
    fauxton/app/addons/documents/templates/upload_modal.html \
    fauxton/app/addons/documents/templates/view_editor.html \
    fauxton/app/addons/documents/tests/resourcesSpec.js \
    fauxton/app/addons/fauxton/templates/api_bar.html \
    fauxton/app/addons/fauxton/templates/breadcrumbs.html \
    fauxton/app/addons/fauxton/templates/footer.html \
    fauxton/app/addons/fauxton/templates/index_pagination.html \
    fauxton/app/addons/fauxton/templates/nav_bar.html \
    fauxton/app/addons/fauxton/templates/notification.html \
    fauxton/app/addons/fauxton/templates/pagination.html \
    fauxton/app/templates/layouts/one_pane.html \
    fauxton/app/templates/layouts/two_pane.html \
    fauxton/app/templates/layouts/with_sidebar.html \
    fauxton/app/templates/layouts/with_tabs.html \
    fauxton/app/templates/layouts/with_tabs_sidebar.html \
    fauxton/assets/css/nv.d3.css \
    fauxton/assets/img/couchdb-site.png \
    fauxton/assets/img/couchdblogo.png \
    fauxton/assets/img/fontawesome-webfont.eot \
    fauxton/assets/img/fontawesome-webfont.svg \
    fauxton/assets/img/fontawesome-webfont.ttf \
    fauxton/assets/img/fontawesome-webfont.woff \
    fauxton/assets/img/FontAwesome.otf \
    fauxton/assets/img/fontcustom_fauxton.eot \
    fauxton/assets/img/fontcustom_fauxton.svg \
    fauxton/assets/img/fontcustom_fauxton.ttf \
    fauxton/assets/img/fontcustom_fauxton.woff \
    fauxton/assets/img/glyphicons-halflings-white.png \
    fauxton/assets/img/glyphicons-halflings.png \
    fauxton/assets/img/linen.png \
    fauxton/assets/img/loader.gif \
    fauxton/assets/img/minilogo.png \
    fauxton/assets/index.underscore \
    fauxton/assets/js/libs/ace/ace.js \
    fauxton/assets/js/libs/ace/ext-static_highlight.js \
    fauxton/assets/js/libs/ace/ext-chromevox.js \
    fauxton/assets/js/libs/ace/ext-statusbar.js \
    fauxton/assets/js/libs/ace/ext-elastic_tabstops_lite.js \
    fauxton/assets/js/libs/ace/ext-textarea.js \
    fauxton/assets/js/libs/ace/ext-emmet.js \
    fauxton/assets/js/libs/ace/ext-themelist.js \
    fauxton/assets/js/libs/ace/ext-keybinding_menu.js \
    fauxton/assets/js/libs/ace/ext-whitespace.js \
    fauxton/assets/js/libs/ace/ext-language_tools.js \
    fauxton/assets/js/libs/ace/mode-javascript.js \
    fauxton/assets/js/libs/ace/ext-modelist.js \
    fauxton/assets/js/libs/ace/mode-json.js \
    fauxton/assets/js/libs/ace/ext-old_ie.js \
    fauxton/assets/js/libs/ace/mode-jsoniq.js \
    fauxton/assets/js/libs/ace/ext-options.js \
    fauxton/assets/js/libs/ace/ext-searchbox.js \
    fauxton/assets/js/libs/ace/theme-crimson_editor.js \
    fauxton/assets/js/libs/ace/ext-settings_menu.js \
    fauxton/assets/js/libs/ace/worker-javascript.js \
    fauxton/assets/js/libs/ace/ext-spellcheck.js \
    fauxton/assets/js/libs/ace/worker-json.js \
    fauxton/assets/js/libs/ace/ext-split.js \
    fauxton/assets/js/libs/ace/snippets/javascript.js \
    fauxton/assets/js/libs/ace/snippets/json.js \
    fauxton/assets/js/libs/ace/snippets/jsoniq.js \
    fauxton/assets/js/libs/almond.js \
    fauxton/assets/js/libs/backbone.js \
    fauxton/assets/js/libs/bootstrap.js \
    fauxton/assets/js/libs/d3.js \
    fauxton/assets/js/libs/jquery.js \
    fauxton/assets/js/libs/lodash.js \
    fauxton/assets/js/libs/nv.d3.js \
    fauxton/assets/js/libs/require.js \
    fauxton/assets/js/libs/spin.min.js \
    fauxton/assets/js/plugins/backbone.layoutmanager.js \
    fauxton/assets/js/plugins/cloudant.pagingcollection.js \
    fauxton/assets/js/plugins/jquery.form.js \
    fauxton/assets/js/plugins/prettify.js \
    fauxton/assets/js/plugins/beautify.js\
    fauxton/assets/less/bootstrap/accordion.less \
    fauxton/assets/less/bootstrap/alerts.less \
    fauxton/assets/less/bootstrap/bootstrap.less \
    fauxton/assets/less/bootstrap/breadcrumbs.less \
    fauxton/assets/less/bootstrap/button-groups.less \
    fauxton/assets/less/bootstrap/buttons.less \
    fauxton/assets/less/bootstrap/carousel.less \
    fauxton/assets/less/bootstrap/close.less \
    fauxton/assets/less/bootstrap/code.less \
    fauxton/assets/less/bootstrap/component-animations.less \
    fauxton/assets/less/bootstrap/dropdowns.less \
    fauxton/assets/less/bootstrap/font-awesome/bootstrap.less \
    fauxton/assets/less/bootstrap/font-awesome/core.less \
    fauxton/assets/less/bootstrap/font-awesome/extras.less \
    fauxton/assets/less/bootstrap/font-awesome/font-awesome-ie7.less \
    fauxton/assets/less/bootstrap/font-awesome/font-awesome.less \
    fauxton/assets/less/bootstrap/font-awesome/icons.less \
    fauxton/assets/less/bootstrap/font-awesome/mixins.less \
    fauxton/assets/less/bootstrap/font-awesome/path.less \
    fauxton/assets/less/bootstrap/font-awesome/variables.less \
    fauxton/assets/less/bootstrap/forms.less \
    fauxton/assets/less/bootstrap/grid.less \
    fauxton/assets/less/bootstrap/hero-unit.less \
    fauxton/assets/less/bootstrap/labels-badges.less \
    fauxton/assets/less/bootstrap/layouts.less \
    fauxton/assets/less/bootstrap/media.less \
    fauxton/assets/less/bootstrap/mixins.less \
    fauxton/assets/less/bootstrap/modals.less \
    fauxton/assets/less/bootstrap/navbar.less \
    fauxton/assets/less/bootstrap/navs.less \
    fauxton/assets/less/bootstrap/pager.less \
    fauxton/assets/less/bootstrap/pagination.less \
    fauxton/assets/less/bootstrap/popovers.less \
    fauxton/assets/less/bootstrap/progress-bars.less \
    fauxton/assets/less/bootstrap/reset.less \
    fauxton/assets/less/bootstrap/responsive-1200px-min.less \
    fauxton/assets/less/bootstrap/responsive-767px-max.less \
    fauxton/assets/less/bootstrap/responsive-768px-979px.less \
    fauxton/assets/less/bootstrap/responsive-navbar.less \
    fauxton/assets/less/bootstrap/responsive-utilities.less \
    fauxton/assets/less/bootstrap/responsive.less \
    fauxton/assets/less/bootstrap/scaffolding.less \
    fauxton/assets/less/bootstrap/sprites.less \
    fauxton/assets/less/bootstrap/tables.less \
    fauxton/assets/less/bootstrap/tests/buttons.html \
    fauxton/assets/less/bootstrap/tests/css-tests.css \
    fauxton/assets/less/bootstrap/thumbnails.less \
    fauxton/assets/less/bootstrap/tooltip.less \
    fauxton/assets/less/bootstrap/type.less \
    fauxton/assets/less/bootstrap/utilities.less \
    fauxton/assets/less/bootstrap/variables.less \
    fauxton/assets/less/bootstrap/wells.less \
    fauxton/app/addons/config/assets/less/config.less \
    fauxton/assets/less/couchdb.less \
    fauxton/app/addons/databases/assets/less/databases.less \
    fauxton/assets/less/fauxton.less \
    fauxton/assets/less/icons.less \
    fauxton/app/addons/logs/assets/less/logs.less \
    fauxton/assets/less/prettyprint.less \
    fauxton/assets/less/variables.less \
    fauxton/bin/grunt \
    fauxton/couchapp.js \
    fauxton/favicon.ico \
    fauxton/Gruntfile.js \
    fauxton/index.html \
    fauxton/package.json \
    fauxton/readme.md \
    fauxton/settings.json.default \
    fauxton/settings.json.sample_external \
    fauxton/tasks/addon/rename.json \
    fauxton/tasks/addon/root/base.js.underscore \
    fauxton/tasks/addon/root/resources.js.underscore \
    fauxton/tasks/addon/root/routes.js.underscore \
    fauxton/tasks/addon/template.js \
    fauxton/tasks/couchserver.js \
    fauxton/tasks/fauxton.js \
    fauxton/tasks/helper.js \
    fauxton/test/mocha/chai.js \
    fauxton/test/mocha/mocha.css \
    fauxton/test/mocha/mocha.js \
    fauxton/test/mocha/sinon-chai.js \
    fauxton/test/mocha/sinon.js \
    fauxton/test/mocha/testUtils.js \
    fauxton/test/runner.html \
    fauxton/test/test.config.underscore \
    fauxton/TODO.md \
    fauxton/CONTRIBUTING.md \
    fauxton/writing_addons.md
