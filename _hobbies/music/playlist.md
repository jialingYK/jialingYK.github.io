---
show: true
width: 4
order: 20
group: <i class="fas fa-music"></i> Music
# The part after "list=" in your YouTube Music playlist link
youtube_playlist: PLM-yRgAj6IVw
---
<div class="p-4">
    <h5><i class="fas fa-headphones"></i> On Repeat</h5>
    <hr />
    <div class="embed-responsive embed-responsive-16by9 rounded-xl">
        <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/videoseries?list={{ page.youtube_playlist }}" title="On Repeat playlist" loading="lazy" referrerpolicy="strict-origin-when-cross-origin" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen></iframe>
    </div>
    <p class="small mt-2 mb-0 text-right">
        <a target="_blank" href="https://music.youtube.com/playlist?list={{ page.youtube_playlist }}"><i class="fab fa-youtube"></i> Open in YouTube Music</a>
    </p>
</div>
