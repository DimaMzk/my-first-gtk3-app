/*
 * SPDX-License-Identifier: GPL-3.0-or-later
 * SPDX-FileCopyrightText: 2021 Dimitry Maizik <dima@dmaizik.ca>
 */


 public class MyApp : Gtk.Application {
    public MyApp() {
      Object (
        application_id: "com.github.dimamzk.my-first-gtk3-app",
          flags: ApplicationFlags.FLAGS_NONE
      );
    }

    protected override void activate () {
      var label = new Gtk.Label(_("Hello World!"));
      var main_window = new Gtk.ApplicationWindow (this) {
        default_height = 300,
        default_width = 300,
        title = _("Hello World!")
      };
      main_window.add(label);
      main_window.show_all();
    }

    public static int main(string[] args) {
      return new MyApp().run (args);
    }
  }

