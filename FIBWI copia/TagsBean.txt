package managebeans;

import java.io.Serializable;


public class TagsBean implements Serializable {
 
    private static final long serialVersionUID = 1L;
 
    private String tags = "";
 
    public String getTags() {
        return tags;
    }
 
    public void setTags(String tags) {
        this.tags = tags;
    }
}