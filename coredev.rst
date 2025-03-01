.. _coredev:

How to Become a Core Developer
==============================

What it Takes
-------------

When you have consistently contributed patches which meet quality standards
without requiring extensive rewrites prior to being committed,
you may qualify for commit privileges and become a core developer of Python.
You must also work well with other core developers (and people in general)
as you become an ambassador for the Python project.

Typically a core developer will offer you the chance to gain commit privilege.
The person making the offer will become your mentor and watch your commits for
a while to make sure you understand the development process. If other core
developers agree that you should gain commit privileges you are then extended
an official offer. How core developers come to that agreement are outlined in
:pep:`13`.

What it Means
-------------

As contributors to the CPython project, our shared responsibility is to
collaborate constructively with other contributors, including core developers.
This responsibility covers all forms of contribution, whether that's submitting
patches to the implementation or documentation, reviewing other peoples'
patches, triaging issues on the issue tracker, or discussing design and
development ideas on the core mailing lists.

Core developers accept key additional responsibilities around the ongoing
management of the project:

* core developers bear the additional responsibility of handling the
  consequences of accepting a change into the code base or documentation.
  That includes reverting or fixing it if it causes problems in the
  Buildbot fleet or someone spots a problem in post-commit review, as well
  as helping out the release manager in resolving any problems found during
  the pre-release testing cycle. While all contributors are free to help out
  with this part of the process, and it is most welcome when they do, the
  actual responsibility rests with the core developer that merged the change
* core developers also bear the primary responsibility for deciding when
  changes proposed on the issue tracker should be escalated to python-ideas
  or python-dev for wider discussion, as well as suggesting the use of the
  Python Enhancement Proposal process to manage the design and justification
  of complex changes, or changes with a potentially significant impact on
  end users

As a result of the additional responsibilities they accept, core developers
gain the privilege of being able to approve proposed changes, as well as being
able to reject them as inappropriate. Core developers are also able to request
that even already merged changes be escalated to python-dev for further
discussion, and potentially even reverted prior to release.

Becoming a core developer isn't a binary "all-or-nothing" status - CPython
is a large project, and different core developers accept responsibility for
making design and development decisions in different areas (as documented
in the :ref:`experts` and :ref:`developers`).

Gaining Commit Privileges
-------------------------

The steps to gaining commit privileges are:

1. A core developer starts a poll at https://discuss.python.org/c/committers/

   - Open for 7 days
   - Results shown upon close

2. The poll is announced on python-committers
3. Wait for the poll to close and see if the results confirm your membership
   as per the voting results required by PEP 13
4. The person who nominated you emails the steering council with your email
   address and a request that the council either accept or reject the proposed
   membership
5. Assuming the steering council does not object, a member of the council will
   email you asking for:

   - Account details as required by
     🔒 https://github.com/python/voters/
   - Your preferred email address to
     subscribe to python-committers with
   - A reminder about the `Code of Conduct`_ and to report issues to the PSF
     Conduct WG

6. Once you have provided the pertinent details, your various new privileges
   will be turned on
7. Your details will be added to 🔒 https://github.com/python/voters/
8. They will update the devguide to publicly list your team membership at
   :ref:`developers`
9. An announcement email by the steering council member handling your new
   membership will be sent to python-committers

.. _Code of Conduct: https://www.python.org/psf/conduct/


Mailing Lists
'''''''''''''

You are expected to subscribe to python-committers, python-dev,
python-checkins, and one of new-bugs-announce or python-bugs-list. See
:ref:`communication` for links to these mailing lists.


.. _contributor_agreement:

Sign a Contributor Agreement
''''''''''''''''''''''''''''

Submitting a `contributor form for Python`_ licenses any code you contribute to
the Python Software Foundation. While you retain the copyright, giving the PSF
the ability to license your code means it can be put under the PSF license so
it can be legally distributed with Python.

This is a very important step! Hopefully you have already submitted a
contributor agreement if you have been submitting patches. But if you have not
done this yet, it is best to do this ASAP, probably before you even do your
first commit so as to not forget. Also do not forget to enter your GitHub
username into your details on the issue tracker.


.. _contributor form for Python: https://www.python.org/psf/contrib/



Pull Request merging
''''''''''''''''''''

Once you have your commit privileges on GitHub you will be able to accept
pull requests on GitHub. You should plan to continue to submit your own
changes through pull requests as if you weren't a core developer to benefit
from various things such as automatic integration testing, but you
can accept your own pull requests if you feel comfortable doing so.


Responsibilities
----------------

As a core developer, there are certain things that are expected of you.

First and foremost, be a good person. This might sound melodramatic, but you
are now a member of the Python project and thus represent the project and your
fellow core developers whenever you discuss Python with anyone. We have a
reputation for being a very nice group of people and we would like to keep it
that way.  Core developers responsibilities include following the `PSF Code of
Conduct`_.

Second, please be prompt in responding to questions. Many contributors to Python
are volunteers so what little free time they can dedicate to Python should be
spent being productive. If you have been asked to respond to an issue or answer
a question and you put it off it ends up stalling other people's work. It is
completely acceptable to say you are too busy, but you need to say that instead
of leaving people waiting for an answer. This also applies to anything you
do on the issue tracker.

Third, please list what areas you want to be considered an expert in the
:ref:`experts`. This allows triagers to direct issues to you which involve
an area you are an expert in. But, as stated in the second point above, if you
do not have the time to answer questions promptly then please remove yourself as
needed from the file so that you will not be bothered in the future. Once again,
we all understand how life gets in the way, so no one will be insulted if you
remove yourself from the list.

Fourth, please consider whether or not you wish to add your name to the
:ref:`motivations` list. Core contributor participation in the list helps the
wider Python community to better appreciate the perspectives currently
represented amongst the core development team, the Python Software Foundation
to better assess the sustainability of current contributions to CPython core
development, and also serves as a referral list for organisations seeking
commercial Python support from the core development community.

And finally, enjoy yourself! Contributing to open source software should be fun
(overall). If you find yourself no longer enjoying the work then either take a
break or figure out what you need to do to make it enjoyable again.


.. _PSF Code of Conduct: https://www.python.org/psf/codeofconduct/
