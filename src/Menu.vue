<template>
<body>
    <div class="sidebar">
        <div class="menu">
            <div class="menu-item active">
                <svg xmlns="http://www.w3.org/2000/svg" class="icon" viewBox="0 0 24 24" fill="white"><path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/></svg>
                <a>Home</a>
            </div>
            <div class="menu-item">
                <svg xmlns="http://www.w3.org/2000/svg" class="icon" viewBox="0 0 24 24" fill="white"><path d="M23.707 22.293l-7.387-7.387A9.468 9.468 0 0 0 19.5 10.5C19.5 4.701 15.299.5 9.5.5S-.5 4.701-.5 10.5 4.701 20.5 10.5 20.5a9.468 9.468 0 0 0 4.406-1.18l7.387 7.387c.195.195.451.293.707.293s.512-.098.707-.293a1 1 0 0 0 0-1.414zM2 10.5c0-4.136 3.364-7.5 7.5-7.5s7.5 3.364 7.5 7.5-3.364 7.5-7.5 7.5-7.5-3.364-7.5-7.5z"/></svg>
                <a>Search</a>
            </div>
        </div>

        <div class="library">
            <div class="library-header">
                <svg xmlns="http://www.w3.org/2000/svg" class="library-icon" viewBox="0 0 24 24" fill="white"><path d="M20.5 3h-17C2.673 3 2 3.673 2 4.5v15c0 .827.673 1.5 1.5 1.5h17c.827 0 1.5-.673 1.5-1.5v-15c0-.827-.673-1.5-1.5-1.5zm-17 1.5h17l-.002 11H3.5v-11zm0 14v-1.5h17V18.5H3.5z"/></svg>
                <h2>Your Library</h2>
            </div>
            <div class="tabs">
                <button class="tab">Playlists</button>
                <button class="tab">Podcasts </button>
                <button class="tab">Albums</button>
                <button class="tab">Artists</button>
            </div>
            <div class="search-bar">
                <input type="text" placeholder="Search">
            </div>
            <div class="recents">
                <ul class="recents-list">
                    <li class="recent-item">
                        <img src="../public/images/Group 11.png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>Liked Songs</span>
                            <span class="track-count">• 234 songs</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (1).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>Johnny Drille</span>
                            <span class="artist-type">Artist</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (2).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>African Heat</span>
                            <span class="playlist-type">Playlist • Spotify</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (3).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>Moody Mix</span>
                            <span class="playlist-type">Playlist • Spotify</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (5).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>Varsity Bars</span>
                            <span class="playlist-type">Playlist • Spotify</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (6).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>ODUMODUBLVCK</span>
                            <span class="artist-type">Artist</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (7).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>Your Top Songs 2023</span>
                            <span class="playlist-type">Playlist • Spotify</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (8).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>2000s HITS THROWBACKS | TOP 100 SONGS</span>
                            <span class="playlist-type">Playlist • Filtr US</span>
                        </div>
                    </li>
                    <li class="recent-item">
                        <img src="../public/images/Mask group (9).png" alt="Liked Songs">
                        <div class="recent-info">
                            <span>Shallipopi, ODUMODUBLVCK - Cast</span>
                            <span class="playlist-type">Playlist • Curatorboy</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</body>
</template>

<style>
body {
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
    background-color: #121212;
    color: #FFFFFF;
}

.sidebar {
    width: 350px;
    background-color: black;
    height: 100%;
    padding: 20px;
    box-sizing: border-box;
}

.menu {
    display: flex;
    flex-direction: column;
    margin-bottom: 20px;
}

.menu-item {
    display: flex;
    align-items: center;
    padding: 10px 0;
    cursor: pointer;
    font-size: 16px;
    color: #b3b3b3;
    transition: color 0.2s;
}

.menu-item.active {
    color: #FFFFFF;
}

.menu-item:hover {
    color: #FFFFFF;
}

.icon {
    width: 24px;
    height: 24px;
    margin-right: 15px;
}

.library-header {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
}

.library-icon {
    width: 24px;
    height: 24px;
    margin-right: 10px;
}

.library-header h2 {
    margin: 0;
    font-size: 20px;
}

.tabs {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
}

.tab {
    cursor: pointer;
    padding: 5px 10px;
    border-radius: 10px;
    background-color: #282828;
    color: #b3b3b3;
    font-size: 14px;
    transition: background-color 0.2s, color 0.2s;
    border: none;
    width: 75px;
    height: 31px;
}

.tab:first-child {
    color: #FFFFFF;
    background-color: #1DB954;
}

.tab:hover {
    color: #FFFFFF;
    background-color: #333333;
}

.search-bar {
    margin-bottom: 20px;
}

.search-bar input {
    width: 100%;
    padding: 10px;
    border-radius: 5px;
    border: none;
    background-color: #333333;
    color: #FFFFFF;
    font-size: 16px;
}

.recents {
    margin-top: 20px;
}

.recents-list {
    list-style: none;
    padding: 0;
    margin: 0;
}

.recent-item {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
    padding: 5px 0;
    cursor: pointer;
    transition: background-color 0.2s;
}

.recent-item img {
    width: 60px;
    height: 60px;
    margin-right: 15px;
    border-radius: 5px;
}

.recent-info {
    display: flex;
    flex-direction: column;
}

.recent-info span {
    font-size: 16px;
    color: #FFFFFF;
}

.track-count,
.artist-type,
.playlist-type {
    font-size: 14px;
    color: #b3b3b3;
}

.recent-item:hover {
    background-color: #282828;
    border-radius: 5px;
    padding: 5px;
}

</style>

<script>
export default {

}
</script>