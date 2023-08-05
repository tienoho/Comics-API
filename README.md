# Comics API

Vietnamese Comics API using scrape technique.

## ❌ Don't use this to crawl image!

### **Base URL**: https://comics-api.vercel.app

## Usage

### **Trending**

> page: number _(option)_

_Path_: /trending?page={page}

### **Genres**

_Path_: /genres

### **Comics By Genre**

> genre_id: string

_Path_: /genres/{genre_id}

### **Search**

> query: string \
> page: number _(option)_

_Path_: /search?q={query}&page={page}

### **Search Suggest**

> query: string

_Path_: /search-suggest?q={query}

### **Recommend Comics**

_Path_: /recommend-comics

### **New Comics**

> page: number _(option)_ \
> status: all | completed | ongoing _(option)_

_Path_: /new-comics?page={page}&status={status}

### **Boy Comics**

> page: number _(option)_

_Path_: /boy-comics?page={page}

### **Girl Comics**

> page: number _(option)_

_Path_: /girl-comics?page={page}

### **Completed Comics**

> page: number _(option)_

_Path_: /completed-comics?page={page}

### **Recent Update Comics**

> page: number _(option)_

_Path_: /recent-update-comics?page={page}

### **Comic Detail**

> comic_id: string

_Path_: /comics/{comic_id}

### **Comic Chapters**

> comic_id: string

_Path_: /comics/{comic_id}/chapters

### **Single Chapter**

> comic_id: string \
> chapter_id: number

_Path_: /comics/{comic_id}/chapters/{chapter_id}

### **Top**

> page: number _(option)_ \
> status: all | completed | ongoing _(option)_

#### > **All Comic**

_Path_: /top?page={page}&status={status}

#### > **Daily Comic**

_Path_: /top/daily?page={page}&status={status}

#### > **Weekly Comic**

_Path_: /top/weekly?page={page}&status={status}

#### > **Monthly Comic**

_Path_: /top/monthly?page={page}&status={status}

#### > **Chapter**

_Path_: /top/chapter?page={page}&status={status}

#### > **Follow**

_Path_: /top/follow?page={page}&status={status}

#### > **Comment**

_Path_: /top/comment?page={page}&status={status}
