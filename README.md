# Templates
Here is weblog templates for BeeBlog.org

## Tags & Templates Guide

Making custom changes to your template is easy, but you will need to know how to
use weblog tags. These tags work with the HTML in your template to create the
content on your weblog.

## How Variables Work
Variables begin with `<%` and end with `%>`. They can be used to output various
bits of content on your weblog. For example, placing `<%Title%>` in your template
will output the title of your weblog. Tags begin with `<>` and end with `</>`.
Any content between them is modified in some way, or looped over and outputted
multiple times. For example, placing `<Entry><%EntryTitle%></Entry>` in your
template will display the title of each of your entries.

## Tags & Variables List

`<%WindowTitle%>` - Weblog title and current page title.
- `<%Title%>` - Weblog title.
- `<%Description%>` - Weblog description.
- `<%Avatar%>` - Weblog owner's avatar URL.
- `<%Email%>` - Weblog owner's email address.
- `<%Calendar%>` - The blog's calendar.
- `<%MainPageURL%>` - Weblog's main page URL.
- `<%ProfileURL%>` - Weblog owner's profile URL.
- `<%ArchiveURL%>` - Weblog's archive page URL.
- `<%FriendsPageURL%>` - Weblog's friends page URL.
- `<%SiteFeedURL%>` - Weblog's RSS feed URL.
- `<%AlbumURL%>` - Photo Album URL
- `<%PodcastURL%>` - Podcast Feed URL
- `<IfMainPage> </IfMainPage>` - Contents only display on the main page.
- `<IfEntryPage> </IfEntryPage>` - Contents only display on the view entry page.
- `<IfArchivePage> </IfArchivePage>` - Contents will only display on the archive page.
  - `<%ArchiveInfo%>` - Weblog's archive list.
- `<IfFriendsPage> </IfFriendsPage>` - Contents will only display on the friends page.
- `<Link> </Link>` - Displays your weblog's custom links.
  - `<%LinkTitle%>` - Link title.
  - `<%LinkURL%>` - Link URL.
- `<Friends> </Friends>` - Displays your list of friends.
  - `<%FriendUsername%>` - Friend's username.
  - `<%FriendURL%>` - Friend's weblog URL.
- `<Members></Members>` - Displays the list of members for this weblog.
  - `<%MemberUsername%>` - Member's username.
  - `<%MemberURL%>` - Member's profile URL.
- `<Categories> </Categories>` - Displays this weblog's entry categories.
  - `<%Category%>` - Category name.
  - `<%CategoryURL%>` - Category URL.
- `<RecentEntry> </RecentEntry>` - Displays a list of your recent entries.
  - `<%RecentEntryTitle%>` - Recent Entry's title.
  - `<%RecentEntryDate%>` - Recent Entry's date.
  - `<%RecentEntryTime%>` - Recent Entry's time.
- `<Entry> </Entry>` - Displays this weblog's entries.
  - `<%EntryTitle%>` - Entry title.
  - `<%EntryAuthor%>` - Author's username.
  - `<%EntryAuthorAvatar%>` - Author's avatar URL.
  - `<%EntryAuthorURL%>` - Author's profile URL.
  - `<%EntryDate%>` - Entry date.
  - `<%EntryTime%>` - Entry time.
  - `<%EntryBody%>` - Entry main content.
  - `<%EntryURL%>` - Entry permanent URL.
  - `<SendThisLink> </SendThisLink>` - Entry "Send This Link" URL.
  - `<IfCategoriesAllowed> </IfCategoriesAllowed>` - Contents will only display if the administrator has enabled entry categories.
    - `<%EntryCategory%>` - Entry category.
