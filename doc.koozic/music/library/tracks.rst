.. _tracks:

Tracks
======

It lists all your music tracks.


Views
-----

A :term:`Tree`, a :term:`Form`, a :term:`Search` and a :term:`Pivot` view.


Actions
-------

In the tree view, 2 actions:

* :term:`Add To Playlist`
* :term:`Play`

In the form view, 4 action buttons:

* :term:`Add To Playlist`
* :term:`Play`
* :term:`Download`
* :term:`Create Link`

A track can be set as favorite and be given a rating. The latters can be used when filtering or
creating dynamic :ref:`playlists`. Custom tags can be defined.


.. _track_fields:


Fields
------

.. glossary::

   Name
      Title of the track. Based on the title ID3 tag. If not present, name of the file.

   Favorite
      Set the track as favorite by starring it.

   Song Infos
      These fields are based on their corresponding ID3 tag.

   Rating
      The rating of the track, from 0 to 5.

   Custom Tags
      These can be used to add information not given in the regular ID3 tags.

   Play Count
      A track is considered played if playback >= 50 % of the track duration.

   Skip Count
      A track is considered skipped if 'Next' or 'Previous' is clicked and playback is < 50 % of the
      track duration.

   Play/Skip Ratio
      The ratio between the two latter counters. If the skip counter is zero, the ratio is the play
      counter (to avoid zero division).

      Only in :ref:`debug_mode`.

   Last Played
   Last Skipped
   Bitrate (kbps)
   File Size (MiB)
   Path
      These are pretty straighforward fields.

   Download Links
      The :ref:`download_links` of the track.
